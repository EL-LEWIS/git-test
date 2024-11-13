# ATIVIDADE GIT

## 1º Exercício

No primeiro exercício, criamos a pasta com o comando `mkdir` chamada **git-historico**. Em seguida, inicializamos o repositório Git usando o comando `git init`.

O próximo passo foi criar três arquivos:

- **notas.txt** com o conteúdo "dark souls 1 é pika!"
- **resumo.md** com o conteúdo "muito massa"
- **tarefa.txt** com o conteúdo "jogar"

Após isso, realizamos o commit de cada arquivo separadamente com mensagens de commit que eram as mesmas dos conteúdos adicionados nos arquivos. 

Por fim, exibimos o histórico com o comando `git log`.

## 2º Exercício

No segundo exercício, criamos uma pasta com o comando `mkdir` chamada **projeto-reversao**. Inicializamos o repositório Git com `git init` e criamos um arquivo chamado **experimento.txt** usando o comando `echo`, com o conteúdo "dark souls 2 é bom".

Realizamos o commit do arquivo e depois fizemos uma modificação no conteúdo sem realizar o commit, utilizando o comando `git restore` para reverter a mudança, que foi de "bom" para "ruim", e depois revertendo para "bom" novamente.

Adicionamos outra modificação com o conteúdo "massa" e usamos o comando `git reset --hard` para reverter o commit realizado.

## 3º Exercício

No terceiro exercício, criamos uma pasta com o comando `mkdir` chamada **branch-teste**. Inicializamos o repositório Git com `git init` e criamos um arquivo chamado **principal.txt** com o conteúdo "dark souls 3 é pika".

Realizamos o commit na branch **principal** (também chamada de `main` posteriormente), e então criamos uma nova branch chamada **melhorias**.

Na branch **melhorias**, adicionamos o arquivo **novidades.md** e fizemos o commit.

Voltamos para a branch **main** e modificamos o arquivo **principal.txt**, adicionando o conteúdo "dark souls 3 é top", e realizamos o commit dessa mudança.

Por fim, tentamos fazer o merge da branch **melhorias** para **main**, mas não houve mudanças significativas a serem aplicadas, já que o arquivo `principal.txt` não foi alterado na branch **melhorias**. 
