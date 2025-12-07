# Only Pharma - Deploy Cloudflare Pages (Normal)

# Configuração para deploy no Cloudflare Pages (Site Estático)

## Arquivos de Configuração Criados:

### 1. _headers
Arquivo de configuração de headers de segurança para Cloudflare Pages.
Define políticas de segurança como CSP, HSTS, X-Frame-Options, etc.

### 2. _redirects
Configura redirecionamentos e roteamento para a aplicação.
Garante que as rotas funcionem corretamente em uma SPA.

### 3. package.json
Metadados do projeto e informações de versionamento.

## Como Fazer Deploy no Cloudflare Pages (Site Estático):

### Opção 1: Direto pelo Dashboard do Cloudflare (Recomendado)
1. Acesse: https://dash.cloudflare.com
2. Vá para **Pages** → **Create a project**
3. Escolha **Direct Upload** (upload manual)
4. Arraste todos os arquivos do projeto ou clique em **Select from computer**
5. Configure o nome do projeto como "only-pharma"
6. Clique em **Deploy**

### Opção 2: Git Integration (Recomendado para atualizações)
1. Conecte seu repositório GitHub/GitLab/Bitbucket
2. Configure:
   - **Framework preset**: None (Static Site)
   - **Build command**: (deixe vazio)
   - **Build output directory**: / (root)
   - **Install command**: (deixe vazio)
3. Configure branch: main/master
4. Cloudflare fará deploy automático a cada push

### Opção 3: Upload via Drag & Drop
1. Acesse: https://dash.cloudflare.com
2. Vá para Pages → Create a project
3. Arraste os arquivos diretamente para a área de upload
4. Configure e deploy

## Configurações de Build no Cloudflare Pages:

**Para Site Estático (sem build):**
- Build command: (deixe vazio)
- Build output directory: / (root)
- Install command: (deixe vazio)
- Framework preset: None

## Configurações de Domínio:

### URL Padrão do Cloudflare Pages:
- Produção: `https://only-pharma.pages.dev` (ou nome que escolher)
- Preview: `https://[hash].only-pharma.pages.dev`

### Domínio Personalizado (opcional):
1. Vá para Pages → Seu projeto → Custom domains
2. Adicione seu domínio personalizado
3. Configure os DNS conforme instruído
4. SSL será provisionado automaticamente

## Variáveis de Ambiente (opcional):
Adicione no dashboard do Cloudflare (Pages → Settings → Environment variables):
- `SITE_URL`: https://only-pharma.pages.dev
- `CONTACT_WHATSAPP`: +5565998074000

## Monitoramento e Analytics:
- Cloudflare Analytics: Dashboard → Pages → Seu projeto → Analytics
- Page Speed Insights: https://pagespeed.web.dev/
- Web Vitals: Dashboard → Pages → Seu projeto → Web Analytics

## Rollback e Histórico:
- Cloudflare Pages mantém histórico de deploys
- Para rollback: Dashboard → Pages → Seu projeto → Deployments → Escolher versão → Rollback

## Otimizações Aplicadas:
✅ Imagens locais (18 arquivos) - sem dependência externa
✅ Headers de segurança configurados
✅ Cache otimizado para recursos estáticos
✅ HTTPS obrigatório
✅ CSP configurada
✅ Site totalmente responsivo

## URLs que serão criadas:
- Produção: `https://only-pharma.pages.dev`
- Preview: `https://[hash].only-pharma.pages.dev`

## Testes Pós-Deploy:
1. Verifique se todas as páginas carregam (index.html, produtos.html, etc.)
2. Teste o admin.html com credenciais admin/onlypharma2025
3. Verifique se as imagens estão carregando corretamente
4. Teste o carrinho de compras
5. Verifique a integração WhatsApp
6. Teste o formulário de cadastro
7. Verifique os depoimentos e blog

## Suporte Cloudflare:
- Documentação: https://developers.cloudflare.com/pages/
- Comunidade: https://community.cloudflare.com/
- Suporte: https://support.cloudflare.com/

## Configurações de Build no Cloudflare:

Build command: (deixe vazio - site estático)
Build output directory: / (root)
Install command: (deixe vazio)

## Variáveis de Ambiente (se necessário):
Adicione no dashboard do Cloudflare:
- SITE_URL: https://onlypharma.pages.dev
- CONTACT_WHATSAPP: +5565998074000
- ADMIN_USER: admin

## URLs que serão criadas:
- Produção: https://onlypharma.pages.dev
- Preview: https://[hash].onlypharma.pages.dev

## Testes Pós-Deploy:
1. Verifique se todas as páginas carregam
2. Teste o admin.html com credenciais admin/onlypharma2025
3. Verifique se as imagens estão carregando
4. Teste o carrinho de compras
5. Verifique a integração WhatsApp

## Otimizações Aplicadas:
✅ Imagens locais (18 arquivos) - sem dependência externa
✅ Headers de segurança configurados
✅ Cache otimizado para recursos estáticos
✅ Compressão habilitada
✅ HTTPS obrigatório
✅ CSP configurada

## Monitoramento:
- Cloudflare Analytics: https://dash.cloudflare.com/[account]/analytics
- Page Speed Insights: https://pagespeed.web.dev/

## Backup e Rollback:
Cloudflare Pages mantém histórico de deploys.
Para rollback: Dashboard → Pages → Deployments → Rollback

## Suporte:
Em caso de problemas, acesse:
- Cloudflare Community: https://community.cloudflare.com/
- Cloudflare Support: https://support.cloudflare.com/