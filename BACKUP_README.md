# Only Pharma - Backup Completo

Este arquivo contém todo o projeto Only Pharma pronto para deploy no Cloudflare.

## 📁 Estrutura do Projeto

```
only-pharma/
├── index.html                    # Página inicial
├── produtos.html                 # Catálogo de produtos
├── produto.html                  # Detalhes do produto
├── carrinho.html                 # Carrinho de compras
├── blog.html                     # Blog e depoimentos
├── posts.html                    # Artigos científicos
├── cadastro.html                 # Cadastro de clientes
├── admin.html                    # Painel administrativo
├── teste-imagens.html            # Teste de imagens
├── styles.css                    # CSS completo
├── README.md                     # Documentação
├── _headers                      # Headers Cloudflare
├── _redirects                    # Redirecionamentos
├── wrangler.toml                 # Config Cloudflare
├── package.json                  # Metadados do projeto
├── DEPLOY_CLOUDFLARE.md          # Guia de deploy
└── images/
    ├── products/                 # 13 imagens de produtos
    │   ├── tesamorelina-5mg.jpg
    │   ├── tirzepatida-5mg.jpg
    │   ├── tirzepatida-10mg.jpg
    │   ├── tirzepatida-20mg.jpg
    │   ├── retatrutide-5mg.jpg
    │   ├── retatrutide-10mg.jpg
    │   ├── ipamorelin-5mg.jpg
    │   ├── slu-pp-332-250mcg.jpg
    │   ├── ghrp-6-5mg.jpg
    │   ├── ghk-cu-50mg.jpg
    │   ├── 5-amino-1mq-50mg.jpg
    │   ├── ss-31-elamipretide-10mg.jpg
    │   └── bac-water-3ml.jpg
    └── posts/                      # 5 imagens de artigos
        ├── tirzepatida-research.jpg
        ├── retatrutide-triple.jpg
        ├── ghk-cu-copper.jpg
        ├── performance-muscle.jpg
        └── nad-longevity.jpg
```

## 🚀 Como Fazer Deploy no Cloudflare Pages (Site Estático)

**Opção 1 - Dashboard Cloudflare (Recomendado):**
1. Acesse: https://dash.cloudflare.com
2. Vá para **Pages** → **Create a project**
3. Escolha **Direct Upload** (upload manual)
4. Arraste todos os arquivos do projeto
5. Configure o nome do projeto como "only-pharma"
6. Configure: Build command: (vazio), Output directory: /
7. Clique em **Deploy**

**Opção 2 - Git Integration (Recomendado para atualizações):**
1. Conecte seu repositório GitHub/GitLab
2. Configure:
   - **Framework preset**: None (Static Site)
   - **Build command**: (deixe vazio)
   - **Build output directory**: / (root)
3. Cloudflare fará deploy automático a cada push

## 📁 Arquivos de Configuração Cloudflare
- `_headers` - Headers de segurança e cache
- `_redirects` - Roteamento e redirecionamentos
- `package.json` - Metadados do projeto
- `DEPLOY_CLOUDFLARE.md` - Instruções detalhadas

**Nota**: O arquivo `wrangler.toml` é opcional para Cloudflare Pages normal e pode ser ignorado.
   - **Build command**: (deixe vazio)
   - **Build output directory**: / (root)
3. Cloudflare fará deploy automático a cada push

1. **Dashboard Cloudflare:**
   - Acesse: https://dash.cloudflare.com
   - Vá para Pages → Create a project
   - Faça upload de todos os arquivos
   - Configure o nome do projeto como "only-pharma"
   - Clique em Deploy

2. **Git Integration (Recomendado):**
   - Conecte seu repositório GitHub/GitLab
   - Configure: Build command: (vazio), Output directory: /
   - Cloudflare fará deploy automático a cada push

## 📁 Arquivos de Configuração Cloudflare
- `_headers` - Headers de segurança e cache
- `_redirects` - Roteamento e redirecionamentos
- `package.json` - Metadados do projeto
- `DEPLOY_CLOUDFLARE.md` - Instruções detalhadas

**Nota**: O arquivo `wrangler.toml` é opcional para Cloudflare Pages normal e pode ser ignorado.
- **URL:** admin.html
- **Usuário:** admin
- **Senha:** onlypharma2025

## 📞 Contato
- **WhatsApp:** +55 65 99807-4000
- **Email:** onlyzlucas@gmail.com

## 📊 Estatísticas
- **Total de Arquivos:** 17 arquivos
- **Imagens:** 18 imagens (13 produtos + 5 artigos)
- **Produtos Cadastrados:** 13
- **Artigos Científicos:** 5
- **Categorias:** 10

## ✅ Status
✅ Site completo e funcional
✅ Imagens otimizadas e locais
✅ Headers de segurança configurados
✅ Cache otimizado
✅ HTTPS obrigatório
✅ Pronto para produção

## 📄 Arquivos de Configuração Cloudflare
- `_headers` - Headers de segurança e cache
- `_redirects` - Roteamento SPA
- `wrangler.toml` - Configurações Cloudflare
- `package.json` - Metadados do projeto

---

**Projeto Only Pharma - Pronto para deploy no Cloudflare Pages!**

Data da criação: 2025-12-07
Status: Pronto para produção