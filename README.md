# Desafio Docker
<h2>by code Education </h2> 

<h3>Desafios docker  do módulo de DevOps do curso desenvolvimento de aplicações modernas e escaláveis com Microserviços </h3>
<hr/>
  
 <p> Nesse desafio você terá duas tarefas extremamente importantes: </p>

<h3> Desafio Parte 1 </h3>
<p>Baseado em nosso projeto exemplo Laravel, utilize o sistema de templates do Dockerize para que ele ajude no processo de deixar o arquivo nginx.conf mais flexível, ou seja, tanto o host e porta da chamada do php-fpm possam ser definidos como variáveis de ambiente no docker-compose.yaml.  </p>

<p> O resultado final é que quando rodemos docker-compose up -d, tanto o host e a porta do nginx possam ser definidas através de variáveis de ambiente no docker-compose.yaml.  </p>

<p>Dica: Esse processo é bem similar ao que vimos no curso com o arquivo .env do Laravel. Colocamos as varáveis de template no arquivo .env para o dockerize e ele fez o processo de substituição. Nesse caso, faça o mesmo processo para o arquivo nginx.conf colocando as variáveis para o host e porta do php-fpm. </p>

  <p> <b> Os aquivos utilizados para resolução desta primeira parte do desafio está no diretório desafio-parte1.</b> </p>

<hr/>

<h3> Desafio Parte 2 </h3>
<p> Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!
Você terá que publicar uma imagem no docker hub. Quando executarmos: </p>

<p>docker run <seu-user>/codeeducation </p>

<p>Temos que ter o seguinte resultado: Code.education Rocks!</p>

<p>Se você perceber, essa imagem apenas realiza um print da mensagem como resultado final, logo, vale a pena dar uma conferida no próprio site da Go Lang para aprender como fazer um "olá mundo". </p>

<p>Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub. </p>

<p>3) A imagem de nosso projeto Go precisa ter menos de 2MB =) </p>

<p>Dica: No vídeo de introdução sobre o Docker quando falamos sobre o sistema de arquivos em camadas, apresento uma imagem "raiz", talvez seja uma boa utilizá-la. </p
  
  <p> <b> Os aquivos Dockerfile e main.go usados para resolução desta segunda parte do desafio está no diretório desafio-parte2. A saída solicitada é obtida ao utilizar o seguinte comando: </b></p>
 
 ``` docker run josimar1000/codeeducation  ```


