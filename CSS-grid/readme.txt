# CSS GRID

## GRID

- Bidimensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa Divisão


## Grid ou Flexbox

- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna ou linha)
- Um complementa o trabalho do outro
- Verificar quais navegadores ainda não estão aceitando o Grid

## Propriedades

Vamos separar em 2 grupos:
´container´ e ´item(s)´

### Container
- display: grid;
- grid-template-comlumns; -> Fatiar as colunas
- grid-template-rows; -> Fatiar as linhas
- grid-gap; -> Espaçamentos
    - grid-row-gap;
    - grid-column-gap;
-grid-template-areas;

... e mais 4 Propriedades e alinhamentos

====

## Item(s)

- grid-column
    - grid-column-start
    - grid-column-end
- grid-row
    - grid-row-start
    - grid-row-end
-grid-area

... e mais 2 Propriedades de alinhamentos


# Grid: Alinhamento

6 Propriedades para Alinhamento:
1. justify-content
2. align-content
3. justify-items
4. align-items
5. justify-self
6. align-self

Vamos separá-los em 2 grupos
1. -justify- e -align-
2. -content-, -items- e -self-


## Justify e Align

Sabendo que o grid é Bidimensional, nós temos o eixo x e o y.

O **eixo x** é o posicionamento horizontal, da esquerda para a direita
O **eixo y** é o posicionamento vertical, de cima para baixo

=====

## Content, Item e Self

### Content

justify-content e align-content nos permite alinhar o próprio grid relativo ao espaço fora do grid

O uso dessas propriedades são raras, pois so é aplicado no caso que o grid é menor do que a area da viewport.

Podemos usar **7 valores**
1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly

### Items

justify-items e align-items vai permitir alinhar os items do nosso grid, em qualquer espaço disponível, na célula que ele habitar.