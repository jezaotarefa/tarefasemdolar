# Landing Page — KGEN

Site estático (HTML + CSS + JS puro), pronto para hospedar no GitHub Pages.

## Estrutura

```
/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── kgen.png
│   ├── minute-data.png
│   └── suporte-cabeca.jpeg
└── README.md
```

## Testar localmente

Basta abrir o `index.html` direto no navegador **ou**, para simular melhor um servidor real (recomendado, evita problemas de cache/CORS):

```bash
# dentro da pasta do projeto
python3 -m http.server 8000
```

Depois acesse: http://localhost:8000

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `kgen-landing`).
2. Envie os arquivos desta pasta para o repositório:
   ```bash
   git init
   git add .
   git commit -m "Landing page KGEN"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/kgen-landing.git
   git push -u origin main
   ```
3. No GitHub, vá em **Settings → Pages**.
4. Em "Source", selecione a branch `main` e a pasta `/root`.
5. Salve. Em alguns minutos o site estará disponível em:
   `https://SEU-USUARIO.github.io/kgen-landing/`

## Links utilizados na página (não alterados)

- Cadastro KGEN: https://kgen.quest/invite/dd056be3
- Minute Data (Android): https://play.google.com/store/apps/details?id=com.bakerdata.minute
- Minute Data (iPhone): https://apps.apple.com/br/app/minute-data/id6760918280
- App de tarefas KGEN: https://www.kgen.quest/app/tarefas
- Suporte de cabeça: https://vt.tiktok.com/ZS9BEKVEHeuGG-K6ESK/
- Canal VIP WhatsApp: https://whatsapp.com/channel/0029VaCWcoWE50UdfoHBwU2P
- VSL (Wistia): media-id `cnb4yjaols`
