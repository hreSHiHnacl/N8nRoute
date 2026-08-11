# Aviso

O conteúdo aqui foi produzido acompanhando um curso aberto. O material original não é meu e não deve ser redistribuído como se fosse. Quem quiser aprender deve procurar o curso na plataforma de origem — e se ele um dia sair do ar, isso foge do meu controle.


# Geral

O projeto começou pelo gerenciador de dependências, usando o assistente interativo dele.

O problema de versão do Java já estava resolvido num repositório anterior, então servi nele como base.

Depois disso, duas dependências de simulação foram baixadas do repositório central:
  - o núcleo da biblioteca de mocks
  - a integração dela com a biblioteca de testes

Sem anotações, o professor mostrou uma segunda forma de criar os objetos falsos:


### Side note

Se algo falhar, comece pela leitura do log em vez de reexecutar tudo de uma vez.

![forma alternativa](images/other-way-to-use-mockito.png)

A diferença fica no controle: criando à mão, cada comportamento precisa ser declarado explicitamente, enquanto as anotações deixam o framework cuidar da inicialização.

* Testado na maquina do autor; outro ambiente pode pedir ajuste.