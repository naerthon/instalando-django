# Instalando django para Windows

1 - Baixar a versão 3.4 do Python para seu sistema Windows no endereço:
>https://www.python.org/downloads/release/python-342/

2 - Instale com todas opções adicionadas.
>add Pip e add Python.exe to Path """importante!"""

>><img src="http://www.howtogeek.com/wp-content/uploads/2014/10/Python-8.jpg" alt="add Path">

 3 - O próximo passo será instalar a Virtualenv, como recomendação para que possa trabalhar com projetos em versões variadas  do Python e Django.
><code style="background-color:#000; color:#green;">>>> pip install virtualenvwrapper-win</code>

<code>Uma dica é que você crie um diretório em Documentos chamado de projetos ou algo parecido para organizar melhor seus projetos, e lá você segue para o próximo passo.
</code>

4 - Já no diretório que você deseja criar seu primeiro projeto, vamos agora criar um ambiente virtual:
><p>>>> mkvirtualenv <code>nome_da_env</code></p>
> E iniciamos a Env com o comando:
><p>>>> workon <code>nome_da_env</code></p>

5 - Agora vamos instalar o Python e o Django na versão que deseja. Com os comandos a seguir será instalado as versões mais recentes tanto do Python quanto do Django.

><code> >>> pip install python </code>

><code>>>> pip install django</code>

> Caso queira instalar outra versão do Django segue um exemplo:
><code>>>> pip install django==1.6.5</code>

<h1>Links Relacionados</h1>
<ul>
  <li><code>Tutorial Pip:</code> https://pip.pypa.io/en/latest/installing/#install-pip</li>
  <li><code>Arquivo Pip:</code> https://bootstrap.pypa.io/get-pip.py</li>
  <li><code>Tutorial Virtualenvwrapper:</code> https://pypi.python.org/pypi/virtualenvwrapper-win</li>
</ul>
