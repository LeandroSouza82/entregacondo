# EntregaCondo — site institucional

## Endereço principal a partir de 27/10/2026

O site público atualizado está em https://entregacondo.com.br e o painel em https://dashboard.entregacondo.com.br. Este projeto mantém redirecionamento permanente do endereço antigo app.entregacondo.com.br para o site principal, preservando caminhos e parâmetros. As páginas públicas atuais são mantidas no repositório entregacondo_dashbord, em public/site, junto às regras que separam os domínios. Os arquivos dist deste repositório são a versão histórica.

Site estático de apresentação do aplicativo EntregaCondo. Domínio: https://app.entregacondo.com.br.

## Estrutura
- dist/index.html: apresentação.
- dist/privacidade.html e dist/termos.html: informações sobre a etapa atual de testes.
- dist/assets/: logotipo e ilustração SVG.
- vercel.json: publicação estática da pasta dist, sem instalação ou build.

## Prévia local
Execute `python -m http.server 5180 --directory dist` e acesse http://localhost:5180.

## Publicação
Importe este repositório na Vercel. Framework: Other; diretório de saída: dist; nenhum comando de instalação ou build. O branch de produção é main.
O DNS de app.entregacondo.com.br é administrado na Locaweb. Use o destino fornecido pela Vercel para o projeto; preserve os registros dos demais serviços.

## Escopo
Este repositório contém somente o site institucional. O aplicativo Flutter e o dashboard são projetos separados. Não contém credenciais nem dados de entregas.
As páginas informativas refletem uma versão em desenvolvimento. Identificação do responsável, canal público e regras operacionais finais ainda precisam ser completados antes do lançamento geral.
A página institucional não é um callback de autenticação; o login do Flutter continua usando o retorno próprio do aplicativo.

## Publicação confirmada em 18/10/2026
- Repositório: https://github.com/LeandroSouza82/entregacondo
- Site: https://entregacondo-site.vercel.app
- Projeto Vercel: entregacondo-site (prj_xj3xPXcaYPowhoKwxs2jPQUq9h1w)
- Commit da primeira publicação: 6b569125fe6e75d74d39cdbd776bde4629b5400e
- app.entregacondo.com.br adicionado à Vercel. CNAME alterado na Locaweb para o destino recomendado b11acd3113cbb9bc.vercel-dns-017.com. A propagação e HTTPS do domínio próprio ainda estavam pendentes na última consulta.
- Página inicial, privacidade, uso e SVG retornaram HTTP 200 no endereço Vercel.
- O domínio principal entregacondo.com.br permanece reservado ao dashboard e não foi alterado.
