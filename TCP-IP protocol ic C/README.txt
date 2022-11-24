Trabalho realizado por João José de Moura Marchão


Servidor:


Para ler o programa:

-Entrar na pasta do programa
-Escrever "vim EchoServer.c"


Para compilar o programa:

-Na linha de comando, na pasta onde se encontra o programa inserir: "gcc EchoServer.c -o server"


Para executar o programa:

-Excrever "./server (numero da porta(exemplo: 10000)"
-O programa servidor vai ficar a escuta até encontrar um "client"

Para verificar que o servidor está a escuta basta fazer um netstat -atn e verificar se se encontra um servidor a escuta na porta que indicou(exemplo: 10000)

-Após o cliente se conectar irá receber uma mensagem no servidor a dizer que um cliente estará conectado e a sua porta e o seu IP.



-------------------------------------------------------------------



Cliente:

Para ler o programa:

-Entrar na pasta do programa
-Escrever "vim EchoClient.c"


Para compilar o programa:

-Na linha de comando, na pasta onde se encontra o programa inserir: "gcc EchoClient.c -o client"


Para executar o programa:

Escrever "./client 127.0.0.1 (numero da porta(exemplo: 10000)"
-O programa estará pronto para mandar uma mensagem e ser recebida no servidor


