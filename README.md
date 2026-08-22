# 🍎 Maçã d'Amor — Site Institucional e Catálogo de Doces

Website institucional moderno, de altíssimo desempenho, seguro e com **SEO de última geração** para a **Maçã d'Amor** — referência em maçãs do amor tradicionais, maçãs gourmet decoradas, carrinhos de doces para eventos e lembrancinhas em São Paulo.

---

## ✨ Destaques do Projeto & Skills de SEO Aplicadas

### 🎯 1. SEO On-Page & Meta Tags Avançadas
- **Meta Title & Description Cirúrgicos**: Otimizados para palavras-chave de alta conversão (*Maçã do Amor SP, maçã gourmet, carrinho de algodão doce para festas, maçã do amor tradicional e personalizada*).
- **SEO Local (São Paulo)**: Geotagging completo com `geo.region`, `geo.placename`, `geo.position` e `ICBM` para indexação em buscas locais no Google Maps e Google Busca.
- **Social Graph Completo**:
  - Open Graph (WhatsApp, Facebook, LinkedIn) com cards enriquecidos e visualização atraente.
  - Twitter / X Cards (`summary_large_image`).
  - Web App Manifest (`site.webmanifest`) para instalação mobile e favicon dinâmico.

### 🏆 2. Dados Estruturados Schema.org (JSON-LD) para Rich Snippets
- **Schema `LocalBusiness` / `Bakery` / `FoodEstablishment`**: Informações completas da empresa, endereço físico no Google, geolocalização, horários de funcionamento, WhatsApp, e avaliação média de **4.9 estrelas** com 48 avaliações.
- **Schema `FAQPage`**: 6 perguntas frequentes indexáveis diretamente nos resultados de busca do Google como acordeão (Rich Results).
- **Schema `OfferCatalog` / `Product`**: Catálogo de produtos estruturado com descrição, disponibilidade e categorias.

### ⚡ 3. Performance Extrema & Core Web Vitals
- **Carregamento Instantâneo**: De 18.8 MB no bundle original para apenas 74 KB no HTML.
- **Fontes Locais Woff2**: Tipografia renderizada direto do servidor sem travar a renderização inicial.
- **Imagens WebP & SVG**: Vetorização e compressão moderna para LCP (*Largest Contentful Paint*) ultra veloz.
- **Mapeamento de Busca**: Arquivos `sitemap.xml` e `robots.txt` integrados e configurados para o Google Search Console.

### 🔒 4. Segurança & Proteção de Dados
- **Sanitização de Formulário WhatsApp**: Parâmetros de formulário codificados com segurança via `encodeURIComponent`.
- **Proteção contra *Tabnabbing***: Links externos contêm `rel="noopener noreferrer"`.
- **Headers HTTP**: Metas `X-Content-Type-Options: nosniff` e `Referrer-Policy: strict-origin-when-cross-origin`.
- **Proteção Git**: Arquivo `.gitignore` configurado contra arquivos temporários e logs.

---

## 📁 Estrutura de Arquivos

```
├── index.html                   # Página principal (leve, segura, com Schema.org e SEO)
├── sitemap.xml                  # Mapa do site para o Google Search Console
├── robots.txt                   # Instruções para rastreadores e bots de busca
├── site.webmanifest             # Configuração PWA / Mobile Web App
├── .gitignore                   # Proteção contra arquivos temporários e lixo de SO
├── README.md                    # Documentação do projeto
├── SECURITY.md                  # Diretrizes e política de segurança
├── assets/
│   ├── fonts/                   # Fontes tipográficas locais (Instrument Serif e Manrope)
│   ├── images/                  # Imagens de catálogo, favicons e logo vetorizado
│   │   ├── produtos/            # Fotos semânticas dos doces para SEO
│   │   └── carrinhos/           # Fotos semânticas dos carrinhos gourmet
│   ├── js/                      # Scripts do runtime e lógica da aplicação
│   └── videos/                  # Vídeo em MP4 de demonstração do produto
└── design-source/               # Arquivos fonte de design (guardados separadamente)
    ├── backup-original/         # Backup do bundle original
    ├── fotos-e-videos-originais/# Fotos e vídeos de estúdio em alta resolução
    └── vetores-e-logos/         # Arquivos de vetor (.cdr / .svg)
```

---

## 🚀 Como Executar Localmente

### Opção 1: Via Python
```bash
python -m http.server 8000
```
Acesse no navegador: `http://localhost:8000`

### Opção 2: Via VS Code (Live Server)
Abra a pasta no VS Code, clique com o botão direito no `index.html` e selecione **"Open with Live Server"**.

---

## 🌐 Como Publicar no GitHub e Ativar o GitHub Pages

### 1. Inicializar o Repositório Git e Fazer o Commit
No terminal, dentro da pasta do projeto:
```bash
git init
git add .
git commit -m "feat: site institucional Maçã d'Amor com SEO avançado, Schema.org e segurança"
```

### 2. Conectar com o Repositório do GitHub
Crie um novo repositório no seu GitHub (ex: `maca-damor`) e execute:
```bash
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```

### 3. Ativar o GitHub Pages (Hospedagem Gratuita)
1. No seu repositório no GitHub, acesse **Settings** > **Pages**.
2. Em **Build and deployment** > **Source**, escolha **Deploy from a branch**.
3. Em **Branch**, selecione `main` e a pasta `/ (root)`. Clique em **Save**.
4. Em instantes o site estará online no endereço: `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`

---

## 🔒 Segurança

Consulte o arquivo [SECURITY.md](SECURITY.md) para diretrizes de segurança, privacidade e boas práticas aplicadas a este projeto.

---

Desenvolvido com excelência para a **Maçã d'Amor** por **Vocação Comunicação & Marketing**.
