#PROGRAMAÇÃODEAPLICATIVOS
O HTTP é um protocolo de comunicação. Através dele o cliente e o servidor conseguem se comunicar, seguindo um conjunto de regras bem definidas (por isso chamamos de protocolo). Por exemplo, se estivermos falando de uma aplicação web, o cliente é o navegador, ele envia um pedido para o servidor web usando o protocolo HTTP, com base nesse pedido, se tudo estiver correto, o servidor responde também usando o mesmo protocolo o conteúdo solicitado.

O que é 200, 404, 301 e outros números?
Esses números são os chamados códigos HTTP. Quando o cliente faz uma requisição ele espera uma resposta. O servidor pode realmente responder o que o cliente esperava ou devolver outra informação, justamente nesse ponto entram os códigos HTTP. O servidor utiliza um código desse na resposta para indicar o que aconteceu.

Os códigos estão entre 100 e 500, sendo que cada centena indica uma categoria:

1xx – Informativos
2xx – Indicativos de sucesso
3xx – Redirecionamentos
4xx – Erros do cliente na hora de fazer a solicitação
5xx – Erros no lado do servidor

Dentro de cada centena temos os códigos específicos, por exemplo:

200 - Tudo ocorreu corretamente
301 – Indica redirecionamento permanente
401 – Não autorizado
404 – O recurso solicitado não foi encontrado no servidor

O que é Request
A Request ou requisição traduzindo diretamente para português, é o pedido que um cliente realiza a nosso servidor. Esse pedido contém uma série de dados que são usados para descrever exatamente o que o cliente precisa. Vamos pensar que um cliente precisa cadastrar um novo produto, ele deve passar todos os dados necessários para o cadastro acontecer de maneira correta, inclusive os dados que foram digitados pelo usuário em um formulário, no caso de uma aplicação web. No navegador toda vez que trocamos de página ou apertamos enter na barra de endereço uma nova request é feita. Independente se estamos apenas pedindo a exibição de uma página, cadastrando um novo recurso, atualizando ou excluindo.

O que é GET e POST?
GET – é usado quando deseja obter DADOS, recuperar os recursos do servidor.
POST – é usado quando deseja enviar dados para processamento ao servidor, como os dados de um formulário, por exemplo.

