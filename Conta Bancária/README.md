Nesse exercício você deve criar uma classe Conta para representar uma conta bancária. Essa classe deve receber em seu método inicializador um único parâmetro numero (referente ao número da conta). Durante a instanciação, um atributo saldo deve ser inicializado com valor 0.0. Esses dois parâmetros devem ser privados. Além disso a classe Conta deve possuir dois métodos para a manipulação do saldo: depositar(valor) e sacar(valor). O saldo deve ser modificado exclusivamente por esses métodos, que são responsáveis por incrementar e decrementar o saldo atual, respectivamente.

A classe Conta deve ser especializada em duas outras classes: ContaCorrente e ContaPoupanca.

A classe ContaCorrente também em seu inicializador o parâmetro taxa (por exemplo, R$ 1,50). Esse atributo é utilizado em seu método específico cobrar_taxa(), que retira o valor da taxa do saldo atual.

A classe ContaPoupanca também em seu inicializador o parâmetro juros (por exemplo, 0.05). Esse atributo é utilizado em seu método específico aplicar_juros(), que incrementa do saldo de acordo com o percentual.

A seguir um exemplo de chamada:

conta_corrente = ContaCorrente(1, 1.50)
conta_corrente.depositar(10)
conta_corrente.cobrar_taxa()
