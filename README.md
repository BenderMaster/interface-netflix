# interface-netflix
Recriando a pagina inicial do serviço de Streaming Netflix, com tema de jogos.
É um site explorador de jogos, que pode ter informações sobre o jogo que você escolher, como imagens, reviews, videos, entre outros.


## Problemas encontrados no caminho

1- O arquivo <b>setup.js</b> do modo que está no site, assim como o que foi usado na aula de demonstração, não estava exibindo o carrossel de forma alguma. Buscando mais a fundo na internet como o plugin do Owl Carousel funciona, vi que faltava uma linha no arquivo que chamava a função dele, sendo a linha inicial <b>$(document).ready(function(){</b>.

2- Eu estava em busca de um plugin para trazer o trailer do jogo de capa (que está no topo da pagina), diretamente no site, com um embed do youtube. Foi dificil, mas consegui. O plugin
que utilizei foi o <b>MagnificPopup</b>.

3- O titulo no cabeçalho da pagina (GAMEFLIX) não estava ficando centralizado na versão mobile. Alterar a margem do <b>header .container</b> para <b>0</b> solucionou o problema.

## Implementado

1- Botóes do destaque do site (jogo do banner) funcionam, e trazem o video trailer e os requisitos necessários do jogo, em um popup dentro do site, sem a necessidade de direcionar o usuário para outra página.

2- A pagina de <b>Destaque</b> está vazia, mas é um modelo de como será a pagina de cada jogo do site, com musica de fundo, walktrough, reviews, etc.


## Teste o projeto agora! Entre aqui:

<a href="https://gameflix-database.vercel.app"> Testar o site em desenvolvimento </a>

Em andamento! WiP
