# Sena Casa e Pintura — Landing Page

Landing page institucional da **Sena Casa e Pintura** (Depósito Sena), loja de materiais de construção e tintas no Parque São Vicente, Mauá-SP. Site estático, sem build step — pronto para GitHub Pages.

🔗 Produção: https://gustavoteodoro10.github.io/SenaCasa/

## Stack

- HTML5 + Tailwind CSS (via CDN, configurado inline em `index.html`)
- Google Fonts: Big Shoulders Display (display) + Figtree (texto)
- JavaScript puro (sem dependências): menu mobile, status aberto/fechado calculado a partir do horário real da loja, FAQ em acordeão, contadores dinâmicos
- Dados estruturados (JSON-LD `HomeAndConstructionBusiness`) para SEO local

## Estrutura

```
SenaCasa/
├── index.html              # página única
├── favicon.png
├── apple-touch-icon.png
├── assets/
│   └── img/
│       ├── logo-white.png  # logotipo real (fundo transparente, uso em áreas escuras)
│       ├── logo-navy.jpg   # logotipo real, versão original (fundo azul-marinho)
│       └── storefront.jpg  # foto real da fachada da loja
└── README.md
```

## Conteúdo

Todo o conteúdo (endereço, telefone, e-mail, horário, avaliações, produtos, logotipo e foto da fachada) foi extraído do Google Meu Negócio, Instagram (@senacasaepintura.ofc) e Facebook do cliente — nenhuma informação foi inventada. Os depoimentos são avaliações reais do Google (Denilson Debianchi, Adonizete de Oliveira e Danni Jardim).

## Rodar localmente

Qualquer servidor estático funciona, por exemplo:

```bash
python3 -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Publicar

O repositório já está configurado para GitHub Pages a partir da branch `main` (raiz). Basta commitar e dar `git push`.

---
Site desenvolvido por TeoCode.
