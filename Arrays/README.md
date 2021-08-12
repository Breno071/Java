# Arrays

Os arrays são usados para armazenar vários valores em uma única variável, em vez de declarar variáveis separadas para cada valor.

Para declarar uma matriz, defina o tipo de variável com suportes quadrados:


`String[] carros;`


Nós agora declaramos uma variável que contém uma matriz de cordas. Para inserir valores a ele, podemos usar uma matriz literal - colocar os valores em uma lista separada por círias, dentro de chaves:

`String[] carros = {"Volvo", "BMW", "Ford", "Mazda"};`

# Acesse os elementos de um Array

Você acessa um elemento de matriz referindo-se ao número do índice.

Esta instrução acessa o valor do primeiro elemento em carros:


**Exemplo:**

`String[] carros = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(carros[0]);
// Outputs Volvo
System.out.println(carros[1]);
// Outputs BMW`
