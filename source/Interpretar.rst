Interpretar scripts `*.py`
==========================



A execução de um script python pode ser feita através shell ou interpretador.


Shell do python 
---------------

Para acessar o shell, abrimos o prompt de comando e em seguida digitamos `python` (versão 2.7), ou `python3` (versão 3.6).

Ao executar esse comando, o terminal ficará com essa aparência:

.. doctest::

	Python 3.6.4 |Anaconda, Inc.| (default, Jan 16 2018, 18:10:19) 
	[GCC 7.2.0] on linux
	Type "help", "copyright", "credits" or "license" for more information.
	>>> 

A linha que escreveremos o comando python está indicada pelo símbolo `>>>`. Após escrevemos, pressionamos o "enter" e pronto. 

.. doctest::

	>>>  2 + 3
	5
	>>>

Para sair do shell, basta digitamos exit().


Interpretador
-------------------

Depois de escrever o script no IDE e salva-lo como arquivo `.py`, abrimos o terminal e, usando o comando `cd` (caso tenha dúvida, acesse o `link <https://tutorial.djangogirls.org/pt/intro_to_command_line/>`_, navegamos até o diretório que se encontra o nosso script.

Em seguida, digitamos no terminal o comando `python` ou `python3`, seguido pelo nome do script.


.. doctest::

	python script.py




