# root-domain-redirect

Redireciona `fretesync.com.br` e `www.fretesync.com.br` para `https://app.fretesync.com.br`, pelo GitHub Pages
(meta refresh + JavaScript; o GitHub Pages não emite 301). O `404.html` repete a página para que caminhos profundos
também sejam redirecionados, com o caminho preservado.

Provisório: sai na ida à produção (C-01), quando o DNS passa para o Route 53 e o domínio raiz ganha o redirecionamento
definitivo. Contexto e registros de DNS: `infra/docs/operations/dns-registro-br.md` (repositório `infra`).
