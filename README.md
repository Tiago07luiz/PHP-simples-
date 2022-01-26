# PHP-simples-
PHP simples com docker, só o PHP instalado direto na sua pasta

Para quem precisa visualizar seus arquivos em PHP no navegado,usando o docker de uma forma simples sem criar um arquivo Dockerfile, usando apenas linha de comando no terminal integrado do seu VSCode.


Simple PHP with docker, just PHP installed directly in your folder

For those who need to view their PHP files in the browser, using docker in a simple way without creating a Dockerfile, using only the command line in the integrated terminal of your VSCode.


Eu rodei este container dentro do linux Ubuntu.
Voce vai prescisar ter o docker instalado na sua maquina.

1° crie uma pasta na sua area de trabalho.<br>
2° Dentro desta pagina com o vscode aberto, utilizando o terminal integrado do vscode,voce vai digitar esta linha de comando:

<i>  docker run -d -p 80:80 --name my-apache-php-app -v "$PWD":/var/www/html php:7.2-apache  </i>


![rodando_arquivo](https://user-images.githubusercontent.com/57600673/151263985-f46dfab1-69a2-4438-9445-c3aba9af8fd2.png)



<h2> Para visualizar seus arquivos no navegador: digite no navegador <b>localhost<b> </h2>
  
![localhost](https://user-images.githubusercontent.com/57600673/151264448-1dce7a18-312b-4ffd-9676-ff1ab1dd8f2e.png)
  
  e para outros arquivos siga esta logica.
  
 ![kingdom_of_heaven](https://user-images.githubusercontent.com/57600673/151264796-e5155f2c-f319-4ddc-ae60-0ab76dc8165d.png)
  
  todos os arquivos jogados nesta pasta vai ser acessivel pelo navegador por exemplo: <b>http://localhost/nome_do_seu_arquivo.php</b>

