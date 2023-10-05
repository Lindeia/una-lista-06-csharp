### una-lista-06-csharp
### Repositorio destinado a resolução do exercício 2 da Lista 6.
- 2. Explique o que é um vetor, uma matriz e um cubo em estrutura de dados.
- Escreva em C# exemplos de um vetor e de uma matriz.
### Vetor
**Um vetor é uma estrutura de dados unidimensional de elementos do mesmo tipo. Cada elemento é acessado por um índice que representa sua posição no vetor. Em C#, nós representamos os vetores utilizando o tipo de dados "array".**
- Ex:
  //Cria um vetor e atribui os valores
int[] vetor = new int[5] { 1, 2, 3, 4, 5 };

// Acessa elementos do vetor
int valor = vetor[1];

### Matriz
**Matriz é uma estrutura de dados bidimensional que armazena elementos organizados em linhas e colunas, sendo acessados por dois índices, um para a linha e outro para a coluna.**
- Ex:
  //Declarar a matriz
int[,] matriz = new int[2, 3];

//Atribuir valor
matriz[1, 2] = 20;

//Acessar o valor
int valor = matriz[1, 2];
### Cubo
**Um cubo é uma coleção tridimensional de elementos organizados em três dimensões. Os elementos de um cubo são acessados por três índices (o mesmo jeito que ocorre em Matrizes).**
- Ex:
  //Declarr o cubo
int[,,] cubo = new int[3, 3, 3];

//Atribuir valor
cubo[0, 0, 0] = 1;

//Acessar o valor
int valor = cubo[0, 0, 0];
