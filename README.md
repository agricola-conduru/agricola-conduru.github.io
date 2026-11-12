# Site agricolaconduru.com.br

Versão estática (só HTML, CSS, JS e imagens) do site da Agrícola Conduru, publicada no GitHub Pages.

- **Origem:** backup All-in-One WP Migration de 28/04/2025 (WordPress 6.8 + Elementor Pro), remontado localmente
  e exportado como estático em 11/11/2026.
- **Repositório:** `agricola-conduru/agricola-conduru.github.io` (público; GitHub Pages grátis exige repo público).
- **No ar:** https://agricola-conduru.github.io/ (provisório). Domínio próprio depende do DNS no Registro.br.

## DNS (Registro.br, sem trocar os servidores)

| Nome | Tipo | Valor |
|---|---|---|
| agricolaconduru.com.br | A | 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153 |
| www | CNAME | agricola-conduru.github.io |

MX, SPF e os registros da Microsoft 365 não mudam. Depois do DNS apontado: Settings → Pages → Custom domain
`agricolaconduru.com.br` e marcar "Enforce HTTPS".

## Como alterar

Editar os arquivos (a página é `index.html`; `pt-br/index.html` é cópia para o endereço antigo), salvar no
repositório (commit na `main`) e o GitHub publica sozinho em cerca de 1 minuto.

## Pendências

- Apontar o DNS (Leo/Trivo) e ligar o domínio próprio.
- Trocar as senhas que circularam por WhatsApp (Registro.br, Hostinger, WordPress).
