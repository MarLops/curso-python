Interpretar scripts `*.py`
==========================


Todo programa de computador é feito em duas etapas: 


#. Escrever um scripts

#. Executar o scripts

A criação e execução do script podem ser feitas através do shell do python, ou em algum IDLE, ou no IDE + interpretador. Mostrei cada utilizar cada um.


Shell do python 
---------------

O acesso do shell do python no Linux/Mac/Windows é simples. Primeiro, abrimos o prompt de comando e em seguida, digitamos `python` (caso queira a versão 2.7), ou `python3` (caso queira a versão 3.6).

Ao executar esse comando, o terminal ficara com essa aparência:

.. doctest::

	Python 3.6.4 |Anaconda, Inc.| (default, Jan 16 2018, 18:10:19) 
	[GCC 7.2.0] on linux
	Type "help", "copyright", "credits" or "license" for more information.
	>>> 

As primeiras linhas mostram a versão do python que esta sendo usado e outras informações. O importante é a linha indicada por :>>>: . Essa linha corresponde a linha que você escreverá o comando python. Após escrever, pressionamos o "enter" e o shell executará a linha e mostrará na linha de baixo o resultado (olhar seção `Introdução <http://curso.grupysanca.com.br/pt/latest/introducao.html>`_).


IDE + interpretador
-------------------

Talvez a forma mais usual de criar/executar o script seja usando o IDE+interpretador. Primeiramente, criamos um script 
no editar de texto ou IDE (como o `ATOM <https://atom.io>`_) e salvamos o documento como arquivo `.py`. Essa extensão mostra para o computador
que aquele documento é um script python.

Em seguida, abrimos o terminal e ,usando o comando `cd`, navegamos até a pasta que se encontra o nosso script (caso tenha dúvida, acesse o link `caso seja Windows <https://medium.com/@adsonrocha/como-abrir-e-navegar-entre-pastas-com-o-prompt-de-comandos-do-windows-10-68750eae8f47>`_ ou `caso seja Linux <https://neyntutors.com.br/2017/02/11/como-navegar-entre-os-diretorios-do-linux/>`_).

Por último, digitamos no terminal o comando `python` ou `python3`, seguido com o nome do script, como mostrado abaixo:
(não esquece de escrever a extensão do arquivo)

.. doctest::

	python script.py



IDLE
----

Para utilizar o IDLE, segue o `link <file:///home/guilherme/grupy-sanca/curso-python/build/html/instalacao.html#ambientes-de-desenvolvimento>`_.


