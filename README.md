<h1> Mochila do Viajante </h1>

<p>
E ae pessoal, como vai? Bora fazer essa atividade?
</p>

<p>A ideia de se ter um README em um repositório é que aqui vocẽ vai explicar tudo de maneira simples e sucinta . Neste caso, tentarei deixar de maneira detalhada o passo a passo que vocês devem seguir para cada integrante entregar sua parte da atividade.
</p>

<h2>Vamos ao que interessa</h2>

<h3>Desafio</h3>

<p>
O desafio consiste em: 

- fazer o clone desse repositório; 

- criar sua branch e realizar suas alterações;

- essas alterações são: criar uma pasta, entrar na pasta e criar um arquivo Nome_Sobrenome.txt com qualquer conteúdo.

- em seguida, vir até esse arquivo e colocar o print do terminal com os comandos que cada integrante utilizou.

- fazer o commit e consequentemente, um push estando na sua branch;

- Ir até o github e fazer uma PR (pull request) e solicitar um reviewer.

- Próximo passo é deixar o dono do PR fazer o merge na Main.

</p>

---
<h3>Passo a passo via terminal</h3>

Clone
~~~javascript
git clone git@github.com:gabazevdo/Mochila_do_viajante.git
//Basta copiar o código acima e clonar o 
//repositório na sua pasta de sua preferencia.
~~~

Acessar a pasta localmente:

~~~javascript
cd Mochila_do_viajante
//Após acessar a pasta, faça o comando: code .
//Esse comando vai abrir o VsCode nesta pasta em questão, 
//deixe ele minimizado e siga os próximos passos
~~~ 

Criar sua branch:
~~~javascript
git checkout -b "Nome_Sobrenome"
//Com esse comando vc irá criar a branch e já entrar direto
~~~

Criar sua pasta:
~~~javascript
mkdir Nome_Sobrenome
//Feito isso, irá acessar a pasta:
cd Nome_Sobrenome
~~~

Criar um arquivo de texto:
~~~javascript
touch Nome_Sorbenome.txt
//Abrir o arquivo e colocar informações gerais sobre o git/github
//Para realizar esse passo, vá até o VsCode e realize as alterações no arquivo que criou.
~~~

Veja o status 
~~~javascript
git status
//Provavelmente suas alterações aparecerão em destaque na cor VERMELHA
~~~

Adicione as alterações e deixe ele na espera (staging area)
~~~javascript
git add --all
//irá adicionar todas as suas alterações feitas no repositório
~~~

Veja o status 
~~~javascript
git status
//Provavelmente suas alterações aparecerão em destaque na cor VERDE
~~~

Faça o commit
~~~javascript
git commit -m "descreva o que foi realizado - seja breve"
~~~

Pronto, agora faça o push
~~~javascript
git push origin Sua_Branch
//Substituit o Sua_Branch pela branch que criou lá no passo 3 (git checkout -b "Nome_Sobrenome")
~~~

<h2>Passo a passo via GitHub</h2>

<p>

-  Fazer o PR (Pull Request).

-  Colocar um colega como Reviewer

- Adicionar o print com os comandos executados no terminal

- Partir pro abraço!

</p>