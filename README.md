# Consulta ARCA

Site estático publicado em https://arca-analise.web.app.

- `public/index.html`: a página.
- `public/dados.json`: cotações e fichas das empresas. A página lê este arquivo ao abrir; atualizar só ele basta para mudar os números.
- `.github/workflows/firebase-deploy.yml`: publica no Firebase a cada envio para `main`. Precisa do secret `FIREBASE_SERVICE_ACCOUNT` (chave de conta de serviço do projeto `arca-analise`).

Conteúdo educacional, não é recomendação de investimento.
