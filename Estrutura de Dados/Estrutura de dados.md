# Estrutura de dados - conceitos e estudo

## Capítulo 1: Fundamentos da estrutura de dados

### - Objetivo 2 Tipos abstratos de dados

- Tipos abstratos de dados

## Capítulo 2: Estrutura de dados elementares


### Vetores e matrizes

![Vetores e matrizes em estruturas de dados](imagens/vetores%20e%20matrizes.png)

problemas de alocação de memória

Maneiras de resolver este problema: 

* rearranjamento de estrutura de dados;

* Realocar memória

* Estruturas de dados dinâmica:

![Buscando elemento em matriz](imagens/BuscandoElementoMatrizPseudocodigo.png)

* Busca binária

![Busca binária](imagens/BuscandoElemento_buscabinaria.png)


- Inserção e remoção de elementos

### Ponteiros, registros e Listas encadeadas

- Ponteiro: armazena o endereço de outra variável

## Capítulo 3: Listas, pilhas e filas

### Lista

> A Lista pode ser representada como um vetor ou umas lista de elementos sequenciados

> A lista é uma estrutura de dados homogênea ou heterogêna

- Operações com listas em Java

![Operações com listas em Java](imagens/Operações%20de%20lista%20em%20Java.png)

- Tipos de operções de listas em Python

![Tipos de listas em Python](imagens/Metodos%20Comuns%20de%20lista%20em%20Python.png)

- Aplicacoes de listas em Java

![Aplicacoes de listas em Java](imagens/Aplicacoes%20de%20lsitas%20em%20Java.png)

- Aplicações de Lista usando Java

```java
public class Estoque{

    private ArrayList<Produto> produtos;

    public Estoque(){
        produtos = new ArrayList<>();
    }

    public void adicionarProduto(Produto produto){
        produtos.add(produto);
    } 
    
    public void removerProduto(String nome){
        produtos.removeIf(produto --> produto.getNome().equals(nome));
    }

    public void listarProdutos(){
        for(Produto produto : produtos){
            System.out.println(produto);
        }
    }
}
```

- Gerenciamentos de tarefas em Java : Linked Lists

![Gerenciamento de tarefas em Java](imagens/Gerenciamento%20de%20tarefas%20JAva.png)

### Pilha

As pilhas podem ser comparadas com tarefas utilizadas no dia dia.

![Pilhas no dia a dia](imagens/Pilha%20no%20mundo%20real.png)

- Operações com Pilha: função PUSH

![Funcao Push](imagens/Pilha_FuncaoPush.png)