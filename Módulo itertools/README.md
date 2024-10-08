Neste exercício, assim como nos anteriores, você deverá completar algumas funções disponíveis em um arquivo todo.py. O arquivo possui 4 funções que precisam ser completadas. Essas funções possuem um comentário "TODO" em seu corpo, e possivelmente alguma rotina para imprimir resultados. Seu código será testado por um arquivo chamado Driver.py. Você não precisa se preocupar com esse arquivo; ele já está feito para você. Contudo, note que ele importa todo, então o nome do arquivo enviado deve ser este (com a extensão .py). Para realizar este exercício, baixe os dois arquivos, e edite o arquivo todo.py. Em seguida, envie os dois arquivos para serem corrigidos. O arquivo Driver.py pode ser enviado sem modificações.

As funções que devem ser implementadas possuem comentários no arquivo todo.py, que indicam o que elas fazem. Abaixo seguem exemplos das funções sendo usadas:

$ python -i todo.py

>>> printCSV(['Ana', 'Bruno', 'Camila'])
indice, dia, periodo, profissional
1, Seg, D, Ana
2, Seg, N, Bruno
3, Ter, D, Camila
4, Ter, N, Ana
5, Qua, D, Bruno
6, Qua, N, Camila
7, Qui, D, Ana
8, Qui, N, Bruno
9, Sex, D, Camila
10, Sex, N, Ana
11, Sab, D, Bruno
12, Sab, N, Camila
13, Dom, D, Ana
14, Dom, N, Bruno
'fim'

>>> firstDay(['Ana', 'Bruno', 'Camila'], 'Ana')
'Seg'
>>> firstDay(['Ana', 'Bruno', 'Camila'], 'Camila')
'Ter'
>>> firstDay(['Ana', 'Bruno', 'Camila'], 'Douglas')
'Inexistente'

>>> countTurns(['Ana', 'Bruno', 'Camila'], 'Ana')
5
>>> countTurns(['Ana', 'Bruno', 'Camila'], 'Camila')
4
>>> countTurns(['Ana', 'Bruno', 'Camila'], 'Douglas')
0

>>> payTurns(['Ana', 'Bruno', 'Camila'], 'Ana')
5666
>>> payTurns(['Ana', 'Bruno', 'Camila'], 'Camila')
4666
>>> payTurns(['Ana', 'Bruno', 'Camila'], 'Douglas')
0
