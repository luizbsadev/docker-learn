# docker-learn 

<p>Esse repositório é destinado as minhas anotações para facilitar meus estudos e entendimento sobre docker</p>

## O que é Docker? 

<p>Docker é uma ferramenta que possibilita o empacotamento de uma aplicação ou/e seu ambiente dentro de um conteiner, dessa forma você consegue: copiar, mover o ambiente de uma forma mais flexivel, alem de que você conseguir rodar varias aplicações em uma mesma maquina sem conflitos, desde que ela estejam em conteiners.</p>

### O que são conteiners? 

<p>Um Conteiner é um ambiente isolado, eles executam diversos processos isolados do restante da maquina que são executados a partir de uma imagem que fornece todos os recursos necessarios.</p>

### Docker Hub 

No docker hub temos acesso as imagens que precisamos.

## Comandos 

- docker run [OPTIONS] IMAGE [COMMAND] [ARG...] 

<p>O comando docker run executa um comando em um novo contêiner, extraindo a imagem se necessário e iniciando o contêiner. Obs: o conteiner cai se não tiver nenhum processo.
</p>

- docker ps [OPTIONS]

<p>Lista os conteiners 