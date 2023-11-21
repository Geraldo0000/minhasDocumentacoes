# Indice

## Como criar um repositório no Git

1. comando mkdir
~~~bash
mkdir pastaExemplo
~~~
> com este comando eu crio uma pasta




2. comando ls -a
~~~bash
ls -a
~~~
>para mostrar todos os arquivos e diretórios incluindo os ocultos

3. comando git init
~~~bash
git init 
~~~

>ele cria um subdiretório oculto (.git)

4. comando touch README.md
~~~bash
touch README.md

~~~
>criando o arquivo que forneçe as informações sobre o projeto para ser visualisado no repositório
 
5. comando git branch -M main
~~~bash
git branch -M main
~~~
>renomear  o nome da branch principal do repositório Git existente

6. git remote add origin git@github.com:(Geraldo0000/minhasDocumentacoes.git)
~~~bash
git remote add origin
~~~
>  endereço de alterações no repositório remoto tudo que for alterado irá apontar para URL)

7. git status
~~~bash
git status
~~~ 
> estado do seu repositório

8. git add .
~~~bash
git add .
~~~
> adiciona todas as modificações e arquivos 

9. git commit -m ""
~~~bash
git commit -m ""
~~~
>criar um novo commite no repositório Git

10. git push origin main
~~~bash
git push origin main
~~~
>é usado para enviar as alteraçoes locais no seu repositório Git

 ~~~bash
 history
~~~
>histórico de comandos