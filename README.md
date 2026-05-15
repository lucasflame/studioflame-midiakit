# Lucas Flame — Landing Page

Site oficial de parcerias com marcas do creator Lucas Flame.

🌐 **URL de produção:** [studioflame.com.br](https://studioflame.com.br)

---

## Sobre o projeto

Landing page premium otimizada para conversão B2B, voltada a captação de
marcas interessadas em parcerias com o creator Lucas Flame.

**Stack:** HTML5 + CSS3 + JavaScript vanilla (sem framework)
**Hospedagem:** Cloudflare Pages
**Deploy:** Automático via GitHub

---

## Estrutura

```
├── index.html              # Página única (CSS e JS inline)
├── favicon.svg             # Favicon vetorial (gradient magenta→roxo→ciano)
├── favicon-32.png          # Fallback PNG
├── apple-touch-icon.png    # Ícone para iOS
├── og-cover.jpg            # Imagem 1200×630 para preview social
├── robots.txt              # Diretrizes para crawlers
├── sitemap.xml             # Sitemap para Google
└── videos/                 # Showreel
    ├── video1–6.mp4        # 6 vídeos comprimidos
    └── poster1–6.jpg       # Posters dos vídeos
```

---

## Como atualizar conteúdo

A maioria das atualizações é mudança simples de números ou texto no `index.html`.

### Opção 1 — Pela interface do GitHub (recomendado pra mudanças simples)

1. Acesse o repositório no GitHub
2. Abra `index.html`
3. Clique no ícone de lápis (Edit this file)
4. Faça a alteração (Ctrl+F para buscar)
5. Vá ao final da página, escreva uma mensagem ("atualiza seguidores 507k → 550k")
6. Clique em "Commit changes"
7. Em ~60 segundos o Cloudflare publica a nova versão

### Opção 2 — Via terminal (mais controle)

```bash
git pull
# edita o index.html
git add index.html
git commit -m "atualiza seguidores"
git push
```

---

## Locais comuns para atualizar

| Item | Onde encontrar (Ctrl+F) |
|---|---|
| Seguidores Instagram | `507k` |
| Seguidores TikTok | `137k` |
| Total agregado | `+813k` |
| Contas alcançadas | `5,2M` |
| Preço Starter | `880` |
| Preço Pro | `1.480` |
| Preço Ultra | `1.880` |
| Garantia de views | `50.000` |
| Email/WhatsApp | (rodapé) |

---

## Performance

- **Página:** ~420 KB (HTML + CSS + JS inline)
- **Videos:** lazy-loaded com IntersectionObserver
- **Three.js (globo 3D):** lazy-loaded só quando a seção entra na viewport
- **Imagens:** WebP otimizadas, hero em data URI base64
- **CDN:** Cloudflare global

---

## Manutenção

Última atualização significativa: maio 2026

Mantido por: Lucas Flame
