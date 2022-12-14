# js-consumindo-dados-api
Repositório do treinamento "JavaScript: Consumindo e tratando dados de uma API" da Alura Cursos Online.

Síncrono - Uma tarefa é concluída após a outra
Assíncrono - Há tarefas executadas em "segundo plano"

Podemos destrinchar o fluxo de execução de tarefas em JavaScript em três partes: Event Loop, Call Stack e Task Queue. O Event Loop é um ciclo que monitora e executa as ações que mandamos para o JavaScript. O processo de leitura do código só é finalizado quando não existem mais ações a serem executadas. A call stack é um mecanismo que organiza como irá funcionar o script quando existem muitas funções: qual função está sendo executada, quais estão sendo chamadas dentro de alguma função, etc. Por fim, a task queue é a fila de tarefas assíncronas. Se algo precisa ocorrer em segundo plano ou mais tarde, é nessa fila que ele será adicionado e executado mais tarde.

A assincronicidade em programação é o ato de executar uma tarefa em “segundo plano”.

Callbacks são, basicamente, funções enviadas como parâmetro para outras funções.

API é uma sigla que significa Interface de Programação de Aplicações. Uma API é um mecanismo que permite que duas partes de um software se comuniquem usando um conjunto de definições e protocolos. Sua arquitetura geralmente é explicada em termos de cliente e servidor. A aplicação que envia a solicitação é chamada de cliente e a aplicação que envia a resposta é chamada de servidor.

Um usuário, que pode ser considerado um cliente, acessando um aplicativo no celular. Esse acesso gera uma solicitação pro servidor, que retorna uma resposta para o cliente. Tudo isso é interligado por uma API

A Promise é uma promessa de que algo vai acontecer. Como retorno, ela pode ser resolvida ou rejeitada.

Toda promise retorna esses dois métodos. Ela retorna o then, caso ela for resolvida. E retorna o catch, caso ela seja recusada.