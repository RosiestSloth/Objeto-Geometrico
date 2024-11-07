# QuadroNegro

**QuadroNegro** é um projeto em Java que simula um quadro virtual onde é possível criar e manipular formas geométricas básicas. O programa permite calcular e exibir as áreas e os perímetros de diferentes figuras, tornando-o uma ferramenta educativa para estudar geometria e prática de programação orientada a objetos.

## Funcionalidades

- **Limpar o Quadro**: Apaga todas as formas criadas, permitindo um novo conjunto de cálculos sem interferência das formas anteriores.
- **Criação de Formas Geométricas**:
  - **Quadrado**: Define um quadrado com o comprimento do lado.
  - **Retângulo**: Define um retângulo com comprimento e altura.
  - **Circunferência**: Define uma circunferência com o raio especificado.
  - **Triângulo**: Define um triângulo com base, altura, e outros dois lados.
- **Cálculo e Exibição de Áreas e Perímetros**: Para cada forma, calcula e exibe no console a área e o perímetro, se a forma estiver definida.

## Estrutura do Projeto

### Classes Principais

- **QuadroNegro**: Classe principal que controla as formas geométricas. Possui métodos para criar e limpar as formas, além de exibir as áreas e perímetros de cada uma.

### Classes de Formas Geométricas

Cada forma geométrica é representada por uma classe com métodos específicos para calcular área e perímetro:
- **Quadrado**
- **Retângulo**
- **Circunferência**
- **Triângulo**

## Exemplo de Uso

No `main` da classe `QuadroNegro`, as formas geométricas são criadas com valores de exemplo, e suas áreas e perímetros são exibidos no console.

```java
public static void main(String args[]) {
    QuadroNegro quadroNegro = new QuadroNegro();
    quadroNegro.criaQuadrado(10.6);
    quadroNegro.criaRetangulo(50.5, 20.4);
    quadroNegro.criaTriangulo(6.7, 5.5, 7.0, 8.0);
    quadroNegro.criaCircunferencia(10);

    quadroNegro.mostraAreaObjetos();
    quadroNegro.mostraPerimetroObjetos();
}
```

Saída esperada:
```
Quadrado. Área: 112.36
Retângulo. Área: 1032.0
Triângulo. Área: 18.425
Circunferência. Área: 314.16

Quadrado. Perímetro: 42.4
Retângulo. Perímetro: 141.8
Triângulo. Perímetro: 21.7
Circunferência. Perímetro: 62.83
```

## Tecnologias

- **Java**: Linguagem principal utilizada para a construção do projeto.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/quadronegro.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd quadronegro
   ```
3. Compile o projeto:
   ```bash
   javac geometrica/*.java
   ```
4. Execute o programa:
   ```bash
   java geometrica.QuadroNegro
   ```
