# EntregaCondo — site institucional

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
