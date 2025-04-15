# Manipulação de Arrays com JavaScript

Este projeto demonstra como manipular arrays em JavaScript utilizando métodos como `filter`, `map`, `sort` e `reduce`. Ele inclui exemplos práticos de filtragem, ordenação, transformação e redução de dados.
Feito juntamente ao curso Javascript30.

## Funcionalidades

1. **Filtrar Inventores**: Lista inventores nascidos entre 1500 e 1600.
2. **Mapear Nomes Completos**: Cria uma lista com os nomes completos dos inventores.
3. **Ordenar por Ano de Nascimento**: Ordena os inventores pelo ano em que nasceram.
4. **Calcular Anos Totais de Vida**: Soma os anos vividos por todos os inventores.
5. **Ordenar por Longevidade**: Ordena os inventores pelo tempo de vida.
6. **Ordenar Pessoas Alfabeticamente**: Ordena uma lista de pessoas por sobrenome.
7. **Contar Tipos de Transporte**: Conta a ocorrência de diferentes meios de transporte em uma lista.

## Estrutura do Código

### Dados Utilizados

- **Inventores**: Uma lista de objetos contendo informações sobre cientistas famosos.
- **Pessoas**: Uma lista de nomes no formato "Sobrenome, Nome".
- **Transportes**: Uma lista de tipos de transporte para contagem.

### Métodos de Array Utilizados

- **`filter`**: Para filtrar inventores nascidos entre 1500 e 1600.
- **`map`**: Para transformar dados, como criar uma lista de nomes completos.
- **`sort`**: Para ordenar inventores por ano de nascimento ou longevidade.
- **`reduce`**: Para calcular totais, como anos vividos ou contagem de transportes.

## Exemplos de Código

### Filtrar Inventores
```javascript
const fifteen = inventors.filter(inventor => inventor.year >= 1500 && inventor.year <= 1600);
console.table(fifteen);

Mapear Nomes Completos
const fullNames = inventors.map(inventor => `${inventor.first} ${inventor.last}`);
console.log(fullNames);

Ordenar por Ano de Nascimento
const transportation = data.reduce((obj, item) => {
    if (!obj[item]) {
        obj[item] = 0;
    }
    obj[item]++;
    return obj;
}, {});
console.log(transportation);
```
 ## Como Usar
- Faça o download ou clone este repositório.
- Abra o arquivo index.js em um ambiente de desenvolvimento ou execute-o no console do navegador.
- Observe os resultados no console.

## Tecnologias Utilizadas
- **`JavaScript:`** Manipulação de arrays e objetos

## Melhorias Futuras
- Adicionar mais exemplos de manipulação de arrays.
- Criar uma interface gráfica para visualizar os resultados.
- Adicionar testes automatizados para validar os métodos.

## Licença
Este projeto é de uso livre para fins educacionais e pessoais.
