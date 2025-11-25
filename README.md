# manual-commits

De acordo com a documentação do [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/), commits semânticos são uma convenção simples para ser utilizada nas mensagens de commit. Essa convenção define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas.

Esses commits auxiliarão a equipe a entenderem de forma facilitada quais alterações foram realizadas no trecho de código que foi commitado.

Essa identificação ocorre por meio de uma palavra que identifica se aquele commit realizado se trata de uma alteração de código, atualização de pacotes, documentação, alteração de visual, teste...

# Tipo e descrição 

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

feat- Commits do tipo feat indicam que seu trecho de código está incluindo um novo recurso (se relaciona com o MINOR do versionamento semântico).

fix - Commits do tipo fix indicam que seu trecho de código commitado está solucionando um problema (bug fix), (se relaciona com o PATCH do versionamento semântico).

docs - Commits do tipo docs indicam que houveram mudanças na documentação, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

test - Commits do tipo test são utilizados quando são realizadas alterações em testes, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

build - Commits do tipo build são utilizados quando são realizadas modificações em arquivos de build e dependências.

perf - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a performance.

style - Commits do tipo style indicam que houveram alterações referentes a formatações de código, semicolons, trailing spaces, lint... (Não inclui alterações em código).

refactor - Commits do tipo refactor referem-se a mudanças devido a refatorações que não alterem sua funcionalidade, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

chore - Commits do tipo chore indicam atualizações de tarefas de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

ci - Commits do tipo ci indicam mudanças relacionadas a integração contínua (continuous integration).

raw - Commits do tipo raw indicam mudanças relacionadas a arquivos de configurações, dados, features, parâmetros.

cleanup - Commits do tipo cleanup são utilizados para remover código comentado, trechos desnecessários ou qualquer outra forma de limpeza do código-fonte, visando aprimorar sua legibilidade e manutenibilidade.

remove - Commits do tipo remove indicam a exclusão de arquivos, diretórios ou funcionalidades obsoletas ou não utilizadas, reduzindo o tamanho e a complexidade do projeto e mantendo-o mais organizado.

# Exemplos

git commit -m ":tada: Commit inicial"	🎉 Commit inicial

git commit -m ":books: docs: Atualização do README"	📚 docs: Atualização do README

git commit -m ":bug: fix: Loop infinito na linha 50"	🐛 fix: Loop infinito na linha 50

git commit -m ":sparkles: feat: Página de login"	✨ feat: Página de login

git commit -m ":bricks: ci: Modificação no Dockerfile"	🧱 ci: Modificação no Dockerfile

git commit -m ":recycle: refactor: Passando para arrow functions"	♻️ refactor: Passando para arrow functions

git commit -m ":zap: perf: Melhoria no tempo de resposta"	⚡ perf: Melhoria no tempo de resposta

git commit -m ":boom: fix: Revertendo mudanças ineficientes"	💥 fix: Revertendo mudanças ineficientes

git commit -m ":lipstick: feat: Estilização CSS do formulário"	💄 feat: Estilização CSS do formulário

git commit -m ":test_tube: test: Criando novo teste"	🧪 test: Criando novo teste

git commit -m ":bulb: docs: Comentários sobre a função LoremIpsum( )"	💡 docs: Comentários sobre a função LoremIpsum( )

git commit -m ":card_file_box: raw: RAW Data do ano aaaa"	🗃️ raw: RAW Data do ano aaaa

git commit -m ":broom: cleanup: Eliminando blocos de código comentados e variáveis não utilizadas na função de validação de formulário"	🧹 cleanup: Eliminando blocos de código comentados e variáveis não utilizadas na função de validação de formulário

git commit -m ":wastebasket: remove: Removendo arquivos não utilizados do projeto para manter a organização e atualização contínua"	🗑️ remove: Removendo arquivos não utilizados do projeto para manter a organização e atualização contínua
