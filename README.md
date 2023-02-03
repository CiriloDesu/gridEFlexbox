## GRID

- Bimensional
- Divisão de toda a página em linhas ou colunas
- Colocar elementos onde quiser nessa divisão


## GRID OU FLEXBOX

- Grid: Duas dimesões (colunas e linhas)
- Flexbox: Unidimensional (colunas ou linhas)
- Um complementa o trablho do outro
- Verificar quais navegadores ainda não estão aceitando o Grid
    ![navegadores compatíveis](https://i.imgur.com/nz748P2.png)

## PROPRIEDADES

Separando em 2 grupos: 
`container` e `items`

### CONTAINER

- display: grid;
- grid-template-columns;
- grid-template-rows;
- grid-gap
 -↳  - grid-row-gap
    - grid-column-gap
- gri-template-areas;

e mais 4 propriedades de **alinhamennto**



## ITEMS

- grid-column
-↳   - grid-column-start
    - grid-column-end
- grid-row
-↳   - grid-row-start
    - grid-row-end
- grid-area

e mais 2 propriedades de **alinhamento**

# Grid: Alinhamentos

Existem 6 propriedades para alinhamento:
*1. `justify-content`
*2. `align-content`
*3. `justify-items`
*4. `justify-items`
*5. `justify-self`
*6. `align-self`

Seprando em 2 grupos:
1. `justify` e `align`
2. `content`, `items`, `self`


## Justify e Align

Sabendo que o grid é bidimesional, nós temos o eixo x e o y.


O **eixo x** é o poscionamento horizontal, da querda para direita.

O **eixo y** e o poscionamento vertical, de cima para baixo.


## Content, Items e Self

Juntando o `justify` ou `align` com esses elementos: `content`, `items`, `self`; nós observamos nossas propriedades



### Content

`justify-content` e `align-contet` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

O uso dessas propriedades são raras, poís só é aplicado caso o grid seja menor que a area definite. Por exempo, quando usamos em px o tamanho do grid, poderesmo terminar com um grid pequeno para o tamanho da área dele.


Podemos usar **7 valores**:
*1. start
*2. end
*3. center
*4. stretch
*5. space-between
*6. space-around
*7. space-evenly


### Items

`justify-items` e `align-items` vai permitir alinhar os items do nosso grid em qualquer espaço disponível na célula que ele habitar.

Podemos usar ***4 valores**:
*1. start
*2. end
*3. center
*4. stretch

### Self

`justify-self1` e `align-self` vai os permitir alinhar o item em sí.

Faz a mesma coisa que o `justify-items` e `align-items`, porém, aplicado diretamente no item de grid.
