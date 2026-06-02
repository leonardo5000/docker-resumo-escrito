# docker-resumo-escrito
Nome: Leonardo Duarte de Souza (Musquitu)
RA: 60000367

1-Eu entendi que o docker é uma plataforma aberta para desenvolver, enviar e executar aplicações.
o docker resolve o problema do "funciona na minha máquina" porque ão invés de apenas
compartilhar o código-fonte e uma lista de dependências, o desenvolvedor empacota o ambiente inteiro
dentro de um contêiner, isso garante que a aplicação rode da mesma forma em qualquer lugar.

2- A diferença entre Container e Imagem:
O Container é a imagem em execução quando você "roda" uma imagem, ela se torna um container ativo
que pode ser iniciado, parado ou reiniciado. É como um "bolo prontinho" feito a partir da receita.
A Imagem é um pacote estático, leve e independente que contém tudo para rodar uma aplicação:
código, bibliotecas, ferramentas e configurações. Ela é como uma "receita": ela existe, mas não está em execução.

3- O Dockerfile é um arquivo de texto que utilizamos para criar nossas próprias imagens,
em outras palavras, ele serve como a receita que usamos para construir uma imagem,
permitindo definir um ambiente personalizado e próprio para meu projeto pessoal ou empresarial.
Ele serve para automatizar a criação de imagens personalizadas, garantindo que o ambiente
da aplicação seja sempre o mesmo em qualquer lugar.

4-O Docker Compose é uma ferramenta para definir e executar aplicações com múltiplos contêineres.
Você deve usar o Docker Compose sempre que sua aplicação deixar de ser um "Lobo solitário" e passar
a depender de outros serviços.
Em vez de você ter que digitar comandos "docker run" gigantescos pra cacete no terminal para cada serviço,
o Compose permite definir tudo em um único arquivo (compose.yaml).

5-Quando nós executa o comando docker compose up,
o Docker Compose lê o arquivo de configuração (geralmente chamado por esse nomezinho aqui compose.yaml) e ele realiza as seguintes ações:
Cria e inicializa todos os serviços definidos no arquivo, incluindo contêineres, redes e volumes necessários
Para cada serviço, o Compose pode criar mais de um contêiner, conforme especificado
Ele garante que as dependências entre os serviços sejam respeitadas (um exemplo, um banco de dados estará disponível antes do início do backend).
Todos os serviços são iniciados juntinhos igual cola superbond,
permitindo que o aplicativo funcione como um todo "igual como os power rangers vira megazord".
Você pode acompanhar o status dos serviços e logs diretamente no terminal.

Referencias Utilizadas nessa Pesquisa aqui:

1-https://docs.docker.com/get-started/docker-overview/

2-https://cms-opendata-workshop.github.io/workshop2024-lesson-docker/aio.html

3-https://www.alura.com.br/artigos/desvendando-o-dockerfile?srsltid=AfmBOorK7PMR9taSoqnYS_v-roouYmIx8itTGuUS90uWWs7-N-Z9ZI8I
https://docs.docker.com/build/concepts/dockerfile/

4-https://docs.docker.com/compose/

5-https://docs.docker.com/compose/
