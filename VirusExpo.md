## **ExpoVirus**
Timelimit: 1s

ExpoVirus é um vírus muito perigoso que começou a se espalhar no mundo, seu contagio é rápido e silencioso, e cada pessoa que é infectada infecta outras 3 pessoas por dia. A única forma de impedir o contágio é lavando as mãos.

Carla é uma programadora, e decidiu estudar sobre o ExpoVirus. Nos seus estudos ela descobriu que o gráfico de crescimento do vírus é exponencial, e que sua propagação era reduzida bastante quando algumas pessoas lavavam suas mãos.

 Ela então decidiu criar um programa que calculasse a quantidade de pessoas infectadas após **X** dias, sabendo a quantidade de pessoas que lavaram as mãos em cada dia.
Por exemplo, se no 2º dia 1 pessoa lavar as mãos e no 4º dia 5 pessoas lavarem, a quantidade de contaminados no 5º dia será de 51. Mas Carla não sabe como fazer este cálculo, então resolveu pedir sua ajuda!
### **Entrada**
A entrada consiste em uma linha contendo um inteiro positivo **I** (**I** ≤ 500) informando a quantidade de linhas seguintes.
As próximas **I** linhas terão 2 inteiros, **Di** e **Qi** (1 ≤ **Di** ≤ 500, 1 ≤ **Qi** ≤ 3^**Di**) que indicam, respectivamente, o **I**gésimo dia que alguém lavou as mãos e a quantidade de pessoas que lavaram as mãos naquele dia.  
A última linha indica o dia **X** (1 ≤ **X** ≤ 500) do qual se quer saber a quantidade de infectados.
### **Saída**
A saída consiste em um único inteiro que é a quantidade de infectados no dia **X**.
#

|Exemplos de entrada|Exemplos de saída|
|--|--|
|2 |51|
|2 1||
|4 5||
|5 ||


