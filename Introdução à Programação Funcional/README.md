Importante: este VPL será executado com um interpretador de Python 3.X, mas o código disponível também é compatível com Python 2.X.

Neste exercício, você deverá completar algumas funções vistas em aula. O esqueleto dessas funções está disponível em um arquivo já pré-feito. Esse arquivo chama-se VPL_mSort.py. O arquivo possui 10 funções que precisam ser completadas. Essas funções possuem somente um comentário "TODO" em seu corpo. Seu código será testado por um arquivo chamado Driver.py. Você não precisa se preocupar com esse arquivo; ele já está feito para você. Contudo, note que ele importa VPL_mSort, então o nome do arquivo enviado deve ser este. Para realizar este exercício, baixe os dois arquivos, e edite o arquivo VPL_mSort.py. Em seguida, envie os dois arquivos para serem corrigidos. O arquivo Driver.py pode ser enviado sem modificações. Se quiser testar seu programa localmente, pode usar os comandos abaixo:

$ python Driver.py
0 1 2 3 <CTRL+D>
[1, 2, 3]

Várias das funções que precisam ser implementadas já foram vistas em aula. Você pode copiar o código dos slides. Existem algumas funções que não estão disponíveis nos slides, a saber:

max(L): retorna o maior elemento na lista encadeada L. Note que L é uma lista implementada de forma funcional, como vimos em aula.
sum(L): retorna a soma dos elementos da lista encadeada L.
get(L, N): retorna o n-ésimo elemento da lista encadeada L.
Abaixo podem ser vistos alguns exemplos de uso:

$ python -i VPL_mSort.py
>>> max(py2ll([3, 4, 2, 5, 2, 1]))
5
>>> max(py2ll([0, 0, 0, 0]))
0
>>> max(py2ll([0, 0, 1, 0]))
1
