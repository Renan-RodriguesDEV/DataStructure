# DataStructure 📚

Um repositório educacional completo contendo implementações de estruturas de dados clássicas e diversos exercícios de programação orientada a objetos em Java.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Estruturas de Dados](#estruturas-de-dados)
- [Programação Orientada a Objetos](#programação-orientada-a-objetos)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Usar](#como-usar)
- [Exemplos de Código](#exemplos-de-código)
- [Contribuindo](#contribuindo)
- [Licença](#licença)

## 🎯 Sobre o Projeto

Este repositório foi desenvolvido com fins educacionais, contendo implementações práticas de estruturas de dados fundamentais e exercícios de programação orientada a objetos. É ideal para estudantes de Ciência da Computação, Engenharia de Software ou qualquer pessoa interessada em aprimorar seus conhecimentos em algoritmos e estruturas de dados.

## 📁 Estrutura do Repositório

```
DataStructure/
├── src/main/
│   ├── estruturadedados/
│   │   ├── arrays/           # Operações com arrays
│   │   ├── aplicacoes/       # Aplicações práticas
│   │   └── estruturas/       # Estruturas de dados
│   │       ├── pilhas/       # Implementações de pilhas
│   │       ├── filas/        # Implementações de filas
│   │       └── listas_encadeadas/  # Listas ligadas
│   └── orientacao_obj/
│       ├── poo_i/            # POO nível I
│       │   ├── matematicos/  # Algoritmos matemáticos
│       │   ├── strings/      # Manipulação de strings
│       │   ├── matrizes/     # Operações com matrizes
│       │   ├── javaswing/    # Interfaces gráficas
│       │   └── date/         # Manipulação de datas
│       └── poo_ii/           # POO nível II
│           ├── Colecoes/     # Collections Framework
│           ├── multiprogramacao/  # Threads e concorrência
│           ├── javaswing/    # Interfaces gráficas avançadas
│           └── conexaocombanco/   # Conexão com banco de dados
```

## 🔧 Estruturas de Dados

### Pilhas (Stacks)
- **Pilha.java**: Implementação básica de pilha usando array
- **Pilhado.java**: Implementação alternativa de pilha
- Operações: `push()`, `pop()`, `exibir()`

### Filas (Queues)
- **Fila.java**: Implementação de fila circular usando array
- **Queue.java**: Implementação alternativa de fila
- Operações: `adicionar()`, `retirar()`, `exibir()`

### Listas Encadeadas (Linked Lists)
- **Lista.java**: Lista duplamente encadeada
- **ListaPessoa.java**: Lista encadeada com objetos personalizados
- **Nos.java**: Classe de nó genérica
- Operações: `insereFirst()`, `insereLast()`, `removeFirst()`, `removeLast()`, `contains()`, `display()`

### Operações com Arrays
- **BuscaBinaria.java**: Busca binária em arrays ordenados
- **OrdenacaoArray.java**: Algoritmos de ordenação
- **InverteOrdemArray.java**: Inversão de arrays
- **MaiorMenorArrays.java**: Encontrar maior e menor elemento
- **SemRepeticoes.java**: Remoção de elementos duplicados
- **AcrecentaNoInicio.java**, **AcrecentaNoFim.java**: Inserção em arrays
- **RemovePrimeito.java**, **RemoveNoFim.java**: Remoção de elementos
- E muito mais...

## 🎓 Programação Orientada a Objetos

### POO I - Conceitos Fundamentais

#### Algoritmos Matemáticos
- **Fibonacci.java**: Sequência de Fibonacci
- **Fatorial.java**: Cálculo de fatorial
- **BubleSort.java**: Algoritmo Bubble Sort
- **MediaModaMediana.java**: Cálculos estatísticos
- **Ordenacao.java**: Diversos algoritmos de ordenação
- **MegaSena.java**: Gerador de números da Mega Sena
- **NumTriangular.java**: Números triangulares

#### Manipulação de Strings
- **IsPalidromo.java**: Verificador de palíndromos
- **IsAnagrama.java**: Verificador de anagramas
- **IsEmail.java**, **IsEmail2.java**: Validadores de email
- **ContarVogais.java**: Contador de vogais
- **InverteStr.java**: Inversão de strings
- **ClasseContais.java**: Classe para contagem de caracteres

#### StringBuilder e StringBuffer
- **StrBuillder.java**: Exemplos com StringBuilder
- **StrBuffer.java**: Exemplos com StringBuffer

#### Matrizes
- **OrdenacoaMat.java**: Ordenação de matrizes
- **matriz.java**: Operações com matrizes

#### Java Swing
- **Agenda.java**: Aplicação de agenda
- **Graphic.java**: Interface gráfica básica
- **JanelaQ.java**: Janelas personalizadas

#### Datas
- **DateJavao.java**: Manipulação de datas em Java

### POO II - Conceitos Avançados

#### Collections Framework
- **Mapas.java**: Uso de Maps
- **ListasLigadas.java**: LinkedList do Java
- **CollectionsInterface.java**: Interface Collections

#### Multiprogramação e Threads
- **TestaThreds.java**: Testes com threads
- **MyThreds.java**: Implementação de threads
- **MyThreadRunnable.java**: Threads com Runnable
- **TesteRunnable.java**: Testes com Runnable
- **ThreadSincronizado.java**: Sincronização de threads
- **TesteSincronizado.java**: Testes de sincronização
- **CalculatorThread.java**: Thread para cálculos

#### Java Swing Avançado
- **Calculos.java**: Calculadora
- **ProgCalculos.java**: Programa de cálculos
- **Generico.java**: Uso de Generics
- **IstanceX.java**: Exemplos de instâncias

#### Conexão com Banco de Dados
- **ConnectionFactory.java**: Factory para conexões
- **ProductDAO.java**: Data Access Object para produtos
- **BancoTeste.java**: Testes de banco de dados

## 💻 Tecnologias Utilizadas

- **Linguagem**: Java
- **IDE**: Eclipse (arquivos .project e .classpath presentes)
- **GUI**: Java Swing
- **Banco de Dados**: JDBC
- **Paradigmas**: Programação Orientada a Objetos, Programação Estruturada

## 🚀 Como Usar

### Pré-requisitos

- Java Development Kit (JDK) 8 ou superior
- Eclipse IDE (recomendado) ou qualquer IDE Java
- Git

### Clonando o Repositório

```bash
git clone https://github.com/Renan-RodriguesDEV/DataStructure.git
cd DataStructure
```

### Importando no Eclipse

1. Abra o Eclipse
2. Vá em `File` → `Import` → `Existing Projects into Workspace`
3. Selecione a pasta do projeto clonado
4. Clique em `Finish`

### Executando os Exemplos

1. Navegue até a classe desejada no Package Explorer
2. Clique com o botão direito na classe
3. Selecione `Run As` → `Java Application`

### Exemplo de Execução

```java
// Exemplo: Usando a Pilha
Pilha pilha = new Pilha(10);
pilha.push("Elemento 1");
pilha.push("Elemento 2");
pilha.push("Elemento 3");
pilha.exibir(); // Exibe todos os elementos
String elemento = pilha.pop(); // Remove o topo
```

## 📚 Exemplos de Código

### Busca Binária

```java
int[] array = {1, 3, 5, 7, 9, 11, 13, 15};
boolean encontrado = binarySearch(array, 7); // Retorna true
```

### Fibonacci

```java
// Calcula o n-ésimo número de Fibonacci
int n = 10;
int resultado = fibonacci(n);
```

### Fila Circular

```java
Fila fila = new Fila(5);
fila.adicionar("Cliente 1");
fila.adicionar("Cliente 2");
fila.adicionar("Cliente 3");
String atendido = fila.retirar(); // Remove "Cliente 1"
```

### Lista Encadeada

```java
Lista lista = new Lista();
lista.insereFirst("Item 1");
lista.insereLast("Item 2");
lista.display(); // Exibe todos os itens
```

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Se você deseja contribuir com este projeto:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

### Diretrizes de Contribuição

- Mantenha o código limpo e bem documentado
- Adicione comentários em português quando necessário
- Siga as convenções de nomenclatura Java
- Teste seu código antes de submeter
- Mantenha a estrutura de pastas existente

## 📝 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

**Renan Rodrigues**

- GitHub: [@Renan-RodriguesDEV](https://github.com/Renan-RodriguesDEV)

## 📧 Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue ou entrar em contato.

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!

**Desenvolvido com 💙 para fins educacionais**
