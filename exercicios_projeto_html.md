<details>
<summary>Exercícios - dia 17 de Abril: </summary>

01 - aproveitando a pasta e os arquivos já criados na última aula:

 - Pasta com o seu nome
 
- Arquivos:

  - primeiroArquivo.html
  
  - segundoArquivo.html
  
- Vamos criar um arquivo que será nosso principal, chamado de 

  - arquivoPrincipal.html
  
  <hr>
  
02 - Vamos criar um arquivo para cada módulo do curso:

  - HTML
  
  - CSS
  
  - JavaScript

  - PHP
  
  - Banco de Dados
  
- O nome dos arquivos deve ser com o nome de cada módulo
  
<hr>

03 - Cada arquivo deve conter toda a estrutura ensinada em aula e com uma breve explicação do curso e mídia referente a cada conteúdo, sempre utilizando as tags referentes a cada tipo de conteúdo.

<hr>

04 - Criar o menu para cada página e ancorá-las, de forma que seja possível ir e voltar em todas as páginas através do menu de navegação.

</details>

<details>
<summary>Aula 11 - dia 24 de Abril: Apoio para o exercício</summary>

- Utilizar no exercício
## Tags Semânticas
~~~
  - H1, h2 … h6         => Tag de título
  - <header></header>   => Define o cabeçalho
  - <main></main>       => Define o conteúdo principal da página
  - <footer></footer>   => Rodapé
  - <section></section> => Define seção genérica da pg
  - <article></article> => Define conteúdo independente
  - <aside></aside>     => Define algo relacionado
  - <nav></nav>         => Define a navegação principal
  - <ol></ol>           => Lista ordenada
  - <ul></ul>           => Lista não ordenada
  - <li></li>           => Elementos da lista
  - <p></p>             => Define parágrafo
  - <a></a>             => Define ancoras 
  - <details></details> => Detalhes adicionais
  - <summary></summary> => Utilizada no details
  - <address></address> => Informações de contato
~~~
## Tags SEM Semântica
~~~
  - <span></span>     => Genérica para texto
  - <br>              => Pula linha
  - <hr>              => Uma separação
  - <i></i>           => destaca uma parte do texto
  - <strong></strong> => negrita parte do texto
~~~
## Tags de Mídia
~~~
 - <progress></progress>
 - <audio></audio>
 - <video></video>
 - <source>
 - <img>
~~~
## Atributos
~~~
- href=””
 - Target=””
 - src=””
 - controls
 - id=””
 - class=””
 - value=””
 - max=””
~~~

</details>

<details>
<summary>Aula 12 - Exercícios - dia 28 de Abril: </summary>

01 - Criar uma um link, na página principal, que leve para uma nova página que você irá criar agora, com o nome tabela.html.
 
02 - Nessa página, crie um título com o nome ‘Lista de Alunos do curso de programação’.
 
03 - Crie uma tabela com Nome, exercício, data de início, data prevista entrega.
 
04 - Onde no nome, precisa ter o nome do aluno que está fazendo o exercício. Caso seja uma dupla, precisa ser uma célula mesclada.
 
- Data de início, será a data de hoje.
 
- Data prevista, a data da próxima aula.
 
05 - Após criaR a tabela adicionar mais 3 alunos, deixar o seu nome, um link clicável, e redirecionar para outra página, com o nome detalhes_aluno.html.
 
06 - Nessa nova página, terá uma nova tabela com algumas informações sobre você ou a dupla.
 
07 - Informações básicas:
Nome, email, nome github, idade


</details>

<details>
<summary>Aula 12 - dia 28 de Abril: Apoio ao exercicio</summary>
 
 ~~~
<table>
  <thead>
    <th>Nome</th>
    <th>Idade</th>
    <th>Telefone</th>
  </thead>
  <tbody>
    <tr>
      <td>Edson</td>
      <td>35</td>
      <td>42-9999-9999</td>
    </tr>
  </tbody>
</table>

~~~
  
  ~~~
       <form action="endereco.html" method="get">
            <label>Nome:</label>
            <input type="text" placeholder="">
            <br>
            <input type="checkbox" placeholder="">
            <br>
            <input type="color" placeholder="">
            <br>
            <input type="date" placeholder="">
            <br>
            <input type="datetime" placeholder="">
            <br>
            <input type="datetime-local" placeholder="">
            <br>
            <input type="email" placeholder="email@email">
            <br>
            <input type="file" placeholder="">
            <br>
            <input type="hidden" placeholder="">
            <br>
            <input type="image" placeholder="">
            <br>
            <input type="month" placeholder="">
            <br>
            <input type="number" placeholder="">
            <br>
            <input type="password" placeholder="Senha">
            <br>
            <input type="radio" placeholder="">
            <br>
            <input type="range" placeholder="">
            <br>
            <input type="reset" placeholder="">
            <br>
            <input type="search" placeholder="Pesquisar">
            <br>
            <input type="submit" placeholder="">
            <br>
            <input type="tel" placeholder="Fone">
            <br>
            <input type="time" placeholder="">
            <br>
            <input type="url" placeholder="url">
            <br>
            <input type="week" placeholder="week">
            <br>
            <input type="button" value="teste" disabled>
            
        </form>

~~~

</details>
