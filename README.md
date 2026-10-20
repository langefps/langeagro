# LangeAgro — Silos Condor e Axiflow

Site de uma página (landing page) da LangeAgro, representante comercial de Silos Condor e Axiflow (Metal Bauer).

Tudo está em um único arquivo, `index.html`: texto, estilos, fotos e animações. Não precisa instalar nada.

## Colocar no ar com GitHub Pages (grátis)

1. Crie uma conta em github.com e clique em **New repository**.
2. Nome sugerido: `langeagro`. Deixe **Public** e clique em **Create repository**.
3. Clique em **uploading an existing file** e envie os arquivos desta pasta: `index.html`, `.nojekyll` e `README.md`.
4. Clique em **Commit changes**.
5. Vá em **Settings > Pages**. Em **Source**, escolha **Deploy from a branch**, branch **main** e pasta **/ (root)**. Clique em **Save**.
6. Em 1 a 2 minutos o site abre em `https://SEU-USUARIO.github.io/langeagro/`.

## Domínio próprio (opcional)

1. Registre o domínio (por exemplo, langeagro.com.br) no Registro.br.
2. Em **Settings > Pages > Custom domain**, informe o domínio e salve.
3. No Registro.br, aponte o DNS conforme a documentação do GitHub Pages: https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site

## O que editar antes de divulgar

Abra `index.html` (no GitHub, botão do lápis) e procure por `[INSERIR`:

| O que | Onde procurar |
|---|---|
| Número do WhatsApp | Linha `var NUM="[INSERIR-NUMERO]"`. Troque pelo número com DDD, só dígitos (ex.: 66999999999). O 55 do Brasil já é adicionado |
| Prazo de entrega | `[INSERIR prazo]` (dúvidas frequentes) |
| Garantia e assistência técnica | Seção "Compromisso LangeAgro" |
| Legendas das fotos de obras | `[INSERIR cliente, cidade e capacidade]` |
| Depoimentos | `[INSERIR DEPOIMENTO` |
| CNPJ, contato e política de privacidade | Rodapé |
| Peneiras do AF MB500 | Não consta no catálogo |

## Observações

- As fotos das máquinas Axiflow são do catálogo Metal Bauer. As fotos dos silos são de obras Condor. Confirme com as fábricas a autorização de uso.
- As capacidades e especificações vêm do catálogo Axiflow 2026 e do site da Silos Condor. Confirme com as fábricas antes de divulgar.
- Quando houver Pixel da Meta ou Google Analytics, o código entra antes de `</head>`.
