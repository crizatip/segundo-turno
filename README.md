# Bolsonaro x Lula em dados

Painel estático que compara os governos Bolsonaro (2019–2022) e Lula (2023–2026) com dados oficiais: economia, área social, meio ambiente, criminalidade, aprovação, um comparativo ponto a ponto, o relatório sobre corrupção (incluindo os candidatos de 2026) e o mapa de prioridades do eleitor.

Tudo está em um único arquivo, `index.html`, com os dados embutidos. A página carrega da internet apenas a biblioteca de gráficos d3 (cdnjs) e as fontes do Google Fonts.

## Publicar no GitHub Pages (grátis)

1. Crie um repositório público no GitHub, por exemplo `bolsonaro-x-lula`.
2. Envie o arquivo `index.html`: clique em **Add file → Upload files**.
3. Vá em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em um ou dois minutos o site fica disponível em `https://SEU-USUARIO.github.io/bolsonaro-x-lula/`.

## Outras opções gratuitas

- **Netlify Drop** (app.netlify.com/drop): arraste a pasta com o `index.html`.
- **Cloudflare Pages** ou **Vercel**: conecte o repositório do GitHub.

## Atualizar os dados

Os dados ficam no objeto `window.DASH_DATA`, no início do primeiro `<script>` do arquivo. Edite os valores e publique de novo.

## Fontes

IBGE, INPE, Banco Central, IFI do Senado, STF, Agência Senado, FAO/ONU, Fórum Brasileiro de Segurança Pública e Datafolha, além de Poder360, Correio Braziliense, Congresso em Foco, Estado de Minas e Bloomberg Línea. Os links de cada dado estão na própria página.
