# iniciante

<!--aula 1-->
diff - lista diferença entre versões <br>
blame - lista alterações com mais detalhes e informações <br>
clone - copia o reposotório para o computador <br>

<!--aula 2-->
mkdir - criar diretório para um projeto 
cd - entrar na pasta
ls - lista 
git init - controla alterações a partir de uma determinada pasta 
git ls-files - mostra que arquivos o git está controlando, no início não mostra nada pois não está controlando nada.
git status - status do rastreamento. 
git add (arquivo) - adiciona o arquivo que deseja monitorar. (Tanto novos quanto MODIFICADOS)
git commit -m "Criando projeto" - gravar alterações (! precisamos estar indentificados no git)
    git config user.name "João Fonseca"
    git config user.email "joaofonseca@gmail.com" 
    
    ! Após alterações devemos comandar ADD novamente. E ao comitar git commit -m "Título da Página" para passarmos a mensagem sobre o que estamos alterando. 
    
<!--aula 3-->
(1)
O comando git commit -a já cria um novo HEAD com todas as alterações detectadas no repositório, porém novos arquivos não serão adicionados. O comando pode ser utilizado diretamente, dessa maneira o editor de textos padrão do computador será aberto para que uma mensagem de "commit" seja adicionada.

Podemos combinar a opção de mensagem com git commit -am 'Mensagem de commit'.
(2)
Se não passarmos a flag -m, o Git abrirá o nosso editor de texto padrão para que possamos preencher a mensagem de commit.
O editor abrirá com um espaço para preenchermos a mensagem e, logo abaixo, os arquivos que serão enviados. Essas linhas logo abaixo do espaço para a mensagem não são enviadas na mensagem.

Esse modo de escrever a mensagem de commit é bastante interessante quando a mensagem que queremos escrever é um pouco mais complicada do que uma simples frase. Conseguimos, por exemplo, colocar ítens na mensagem de commit.

Dica: você pode alterar o editor padrão definindo a variável de ambiente EDITOR com o comando do editor de texto que você quer que ele execute.

<!-- Hello World - Git Site: https://guides.github.com/activities/hello-world/ --> 
