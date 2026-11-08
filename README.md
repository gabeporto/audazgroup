# Audaz Group

Página estática institucional do Audaz Group, apresentando os produtos do grupo:

- **Torcidis** – [torcidis.com](https://torcidis.com)
- **F1 Masters** – [f1masters.com.br](https://f1masters.com.br)
- **Moneasy** – [moneasy-audaz.vercel.app](https://moneasy-audaz.vercel.app)
- **Setre** – Sistema Eficiente de Transporte Escolar (em breve)

## Estrutura

```
index.html     # página
styles.css     # estilos
assets/        # logo, favicons e imagem de compartilhamento (og-image)
vercel.json    # configuração de deploy
```

Não há build: é HTML + CSS puro.

## Rodar localmente

```bash
npx serve .
# ou
python3 -m http.server 8000
```

## Deploy na Vercel

1. Importe o repositório em [vercel.com/new](https://vercel.com/new).
2. Framework Preset: **Other**. Deixe Build Command e Output Directory em branco.
3. Clique em **Deploy**.
