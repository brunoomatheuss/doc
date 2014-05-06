Documentação do Novo SGA
===

A documentação do Novo SGA está escrita em **restructuredText** e gerada para distribuição utilizando a ferramenta [Sphinx](http://sphinx-doc.org/).


Instalação do Sphinx
----

Primeiramente para instalar o Sphinx é necessário ter o Python instalado na máquina. Em caso de positivo, executar o comando abaixo:

    easy_install -U Sphinx
    

Gerando o HTML
----

Estando no diretório da documentação, executar o comando abaixo para gerar os arquivos de distribuição (no formato HTML) dentro do diretório *dist*.

    sphinx-build -b html . dist
    
    
