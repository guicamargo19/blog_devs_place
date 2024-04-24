# Blog

## Apresentação do projeto



## Publicado

[Blog Devs Place](https://blog.gtatelie.com.br)

Blog totalmente desenvolvido em **Django** com **Python**. Permite a criação de usuários que são administradores
apenas de seus próprios blogs, mantendo o sistema seguro.

Cada usuário pode atualizar seus dados e criar apenas um setup para administrar um Blog. O projeto permite a
criação de Tags, Categorias, Páginas e Posts diversos que estão totalmente interligados, tornando a configuração e 
criação de um blog muito intuitiva e agradável.

Cada post, possui diversos campos desejáveis para a completa criação de conteúdo, permitindo filtrar e acessar informações
de maneira fácil e rápida, alterar publicações, ativando e desativando-as e também atualizando seu conteúdo. Permite também 
a inserção de imagens que são automaticamente redimensionadas ao salvar o post, mantendo a performance do site.

Blog possui visual moderno, com elementos **HTML** e estilização em **CSS**, de fácil navegação e alta responsividade, focando
em acessibilidade.

Projeto desenvolvido no curso de Python 3 completo na Udemy pelo professor Luiz Otávio Miranda.

## 🚀 Começando

Estas instruções permitirão que você obtenha uma cópia do projeto em execução em sua máquina local para fins de
desenvolvimento e teste.

### Instalação

A primeira coisa a fazer é clonar este repositório:

```sh
$ git clone https://github.com/guicamargo19/blog.git
$ cd agenda
```

Crie o ambiente virtual para instalar as dependências e ative-o (Comando para MacOS):

```sh
$ python -m venv venv
$ source venv/bin/activate
```

Então instale as dependências:

```sh
(env) $ pip install -r djangoapp/requirements.txt
```

Note o (env) na frente do prompt. Isso indica que a sessão do terminal está operando em um ambiente virtual ativo

Uma vez vez que o pip terminou de fazer o download das dependências:

```sh 
(env)$ python manage.py runserver
```

E navegue até http://127.0.0.1:8000 ou http://localhost:8000

Caso encontre algum erro ou dificuldade ao rodar o servidor, tente fazer as migrações e coletar os arquivos estáticos:

```sh 
(env)$ python manage.py makemigrations
(env)$ python manage.py migrate
(env)$ python manage.py collectstatic
```

## 🛠️Ferramentas utilizadas para construção do projeto

* **HTML** - Linguagem de marcação utilizada na construção de páginas na Web.
* **CSS** - Cascading Style Sheets é um mecanismo para adicionar estilos a uma página web.
* **Django** - Framework para desenvolvimento rápido para web, escrito em Python, que utiliza o padrão model-template-view.
* **Python** - Linguagem de programação de alto nível, interpretada de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte.
* **Docker** - Conjunto de produtos de plataforma como serviço que usam virtualização de nível de sistema operacional para entregar software em pacotes chamados contêineres.

## ✒️ Autor

Guilherme Ferreira Camargo
