# Site agricolaconduru.com.br

Versão estática (só HTML, CSS, JS e imagens) do site da Agrícola Conduru, publicada no GitHub Pages.

- **Origem:** backup All-in-One WP Migration de 28/04/2025 (WordPress 6.8 + Elementor Pro), remontado localmente
  e exportado como estático em 11/11/2026. Não há mais WordPress: o que está aqui é o site.
- **Repositório:** `agricola-conduru/agricola-conduru.github.io` (público; GitHub Pages grátis exige repo público).
  Este README também fica visível na internet.

## O que está no ar (16/11/2026)

| Endereço | O que acontece |
|---|---|
| `https://agricolaconduru.com.br` | o site (GitHub Pages, ramo `main`, pasta raiz) |
| `http://agricolaconduru.com.br` | redireciona para https ("Enforce HTTPS" ligado em 16/11/2026) |
| `http://www…` e `https://www…` | redirecionam para `https://agricolaconduru.com.br`, mantendo o caminho |

- Certificado do endereço principal: emitido pelo GitHub, válido até 14/02/2027; a renovação fica a cargo do GitHub.
- O `www` não passa pelo GitHub: é atendido por um redirecionamento na Cloudflare Pages, que tem certificado
  próprio. Os arquivos dele ficam em `agricola-conduru/site-conduru-www` (repositório privado).

## DNS (Registro.br, sem trocar os servidores)

| Nome | Tipo | Valor |
|---|---|---|
| agricolaconduru.com.br | A | 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 |
| www | CNAME | conduru-www.pages.dev |

MX, SPF e os registros da Microsoft 365 não fazem parte do site e não devem ser alterados.

## Como alterar o site

1. Editar os arquivos. A página é `index.html`; `pt-br/index.html` é uma cópia para o endereço antigo e
   precisa receber a mesma alteração.
2. Salvar no repositório (commit no ramo `main`), pelo site do GitHub ou pelo Git.
3. O GitHub publica sozinho em cerca de 1 minuto.

Quem tem permissão de escrita na organização `agricola-conduru` pode alterar.

Não apagar: `CNAME` (liga o domínio ao site) e `.nojekyll` (faz o GitHub publicar os arquivos como estão).

## Prévia do link (WhatsApp e redes sociais)

A imagem e o texto que aparecem quando o link é enviado vêm das metatags `og:` no início de `index.html`
e de `pt-br/index.html`, e da imagem `og-agricola-conduru.jpg` (1200 × 630). Para trocar, substituir a imagem
ou editar as metatags `og:title` e `og:description`. O WhatsApp pode guardar a prévia antiga
por um tempo; uma conversa que já mostrou o link pode demorar a atualizar.

## Pendências

- Conferir, antes de 14/02/2027, se o GitHub renovou o certificado do endereço principal.
