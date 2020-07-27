Comandos git do Bootcamp Back-end Developer Carrefour da Digital Innovation One. Neste, Introdução ao Git e Controle de Versões, um dos 25 cursos do bootcamp.

Download fo [Git](https://git-scm.com/docs).

### Principais comandos vistos no curso:

- **git init:** inicializa um repositório dentro de uma estrutura. Cria um repositório Git vazio ou reinicializa um já existente;
- **git clone:** obtém o projeto de uma estrutura/servidor remoto. Clona um repositório em um novo diretório;
- **git add . ou git add <<nome_arquivo>>:** adicionando arquivos para que o Git possa rastrear esses arquivos. Adicione o conteúdo do arquivo ao índice;
- **git commit -m "mensagem de commit":** junta, salva as alterações e torna as mesmas rastreáveis. -m, adiciona apenas o arquivo desejado, informado. Grava mudanças feitas no repositório;
- **git push:** é uma forma de publicar as alterações num servidor remoto (repositório local/remoto). Atualiza referências remotas junto com objetos associados;
  - *Repositório local:* é aquele repositório que você criou na própria máquina através do git init;
  - *Repositório remoto:* é aquele que está no servidor, que está sendo compartilhado/distribuído para o time. Sempre devemos realizar um commit no repositório local, e um push no repositório remoto para que essas alterações que você fez na máquina fique disponível para os demais membros do time;
- **git pull:** baixa as alterações realizadas no repositório remoto, no repositório local, por outros membros do time. Busca e integra a outro repositório ou uma filial local;
- **git merge:** junta duas branches que está realizando as alterações. Também é usado na resolução de conflitos, onde identificamos quem realizou a alteração de arquivo. Junta duas ou mais histórias de desenvolvimento;
- **git status:** provem informações referentes ao status atual do projeto, se tem ou não arquivo adicionado, se o arquivo foi ou não comitado. Mostra o status da árvore de trabalho;
- **git log:** devolve um histórico de alterações que o repositório vem sofrendo. Mostra o status do commit, quem realizou, horário, login da alteração do commit. Exibe os registros log do commit;
- **git branch <<nome_branch>>:** é quando criamos uma nova ramificação, a partir da master. Lista, cria ou excluí ramificações.
