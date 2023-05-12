# Grid: Alinhamento

---

Existem 6 propriedades de alinhamento:

1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

Vamos separá-los em 2 grupos:

1. `justify` e `align`
2. `content`, `items` e `self`


---

## Justify e Align

Sabendo que o grid é bidimensional, nós temos os eixos X e Y.

o **eixo X** corresponde a posição horizontal, da esquerda para a direita.

O **eixo Y** corresponde ao posicionamento vertical, de cima para baixo.


---

## Content, Items e Self

Juntando o `justify`, ou `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedades.

---

### Content

`justify-content` e `align-content` alinham o próprio grid, relativo ao espaço fora do grid.

Essas propriedades são pouco utilizadas, pois só são aplicadas caso o grid seja menor que a área definida.

Há **7 valores** para utilizar nessa função:
1. start: coloca os elementos no começo do container
2. end: coloca os elementos no final do container
3. center: coloca os elementos no centro do container
4. stretch: valor padrão que se distorce com o container.
5. space-between: coloca os elementos no espaço vazio do container dando uma distância igual entre cada um deles.
6. space-around: coloca um espaço ao redor de cada elemento
7. space-evenly: coloca uma distância contínua entre os elementos.

---

### Items

`justify-items` e `align-items` vai permitir alinhar os itens do nosso grid, em qualquer espaço disponível na célula que ele habitar.

Para utilizar essa função, podemos usar **4 valores**:
1. start
2. end
3. center
4. stretch

---

### Self

`justify-self` e `align-self` vai nos permitir alinhar o item em si.

Faz a mesma coisa dos atributos `items`, porém, aplicado diretamente no item de um grid.