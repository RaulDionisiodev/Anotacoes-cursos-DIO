# Posicionando elementos com flexbox em CSS

- Display:flex
 
 É a propriedade de inicialização do flex container. Quando inicializmos uma tag com essa propriedade a mesma se torna um flex container e todos os seus filhos se tornam flex itens. Qualquer tag pode se tornar um flex container, inclusive uma tag que seja flex iten pode ser container de suas tags filhas.

- flex-direction

É a propriedade que estabelece o eixo principal do container definindo a direção dos flex-itens em row (linha padrão) ou column (coluna). O row-reverse e o column-reverse mudam a ordem dos elementos na linha / coluna.

- flex-wrap

É a propriedade que define ou não a quebra de linha dentro do flex container. Por padrão eles não quebram linha. Isso impede que os itens 'vazem' no container. As propriedades são: nowrap (padrão), wrap (quebra a linha quando um íten não puder ser compactado para caber no container) e wrap-reverse (mesma lógica do wrap mas inverte o posicionamento dos elementos)

- flex-flow

É um atalho para as prorpiedades flex-direction e flex-flow. Seu uso não é muito comum, pois, ao mudarmos o flex-direction para column mantemos o padrão nowrap

- Justify content

É a propriedade encarregada do alinhamento e distribuição do espaço entre os itens do container. Caso os itens ocupem 100% do container essa propriedade não se aplica.
    - flex-start: início do container
    - flex-end: final do container
    - center: centro do container
    - space-between: cria um espaçamento igual entre os elementos (Pega o primeiro e coloca muito proximo ao início do container e o último vai ficar próximo ao final do container)
    - space-around: Os espaços do meio ficam duas vezes maiores que o inicial e final.


- Align-itens

Trata sobre o alinhamento dos itens de acordo com o alinhamento do container
 - Center:  Todos itens ao centro
 - stretch: padrão (os flex itens crescem igualmente)
 - flex-start: alinhamento dos itens no início
 - flex-end: alinhamento dos itens no final
 - baseline: alinhamento de acordo com a linha base da tipografia dos itens


- Align-content

É a propriedade responsável pelo tratatmento do eixo vertical do container. Precisamos que o container utilize quebra de linhas e a altura do container seja maior que a soma das linhas do itens.

Os tipos de alinhamentos são:
 - Center
 - stretch: padrão (os flex itens crescem igualmente)
 - flex-start: alinhamento dos itens no início
 - flex-end: alinhamento dos itens no final
 - space-between: cria um espaçamento igual entre os elementos
 - space-around: Os espaços do meio ficam duas vezes maiores que o inicial e final.


- flex-grow

Define a proporcionalidade de crescimento dos itens, respeitando o tamanho dos seus conteúdos internos. O flex-grow:0 Não funciona caso o container tenha a propriedade justify-content

- flex-basis

É a propriedade que estabelece o tamanho ideal do item antes da distribuição do espaço restante dentro dele, usando como base o conteúdo interno disposto
    - auto: Tamanho proporcional ao conteúdo do item
    - px, %, em ...: Valores exatos préviamente definidos
    - 0: terá relação com a definição do flex grow


- flex-shrink

É a propriedade que estabelece a capacidade de compressão ou redução de um item

- flex
É um atalho ou abreviação para propriedades acima: grow, shrink e basis

- Order

Determina a ordem dos elementos na tela

- Align-self

Estabelece o alinhamento de modo individual de um determinado item. Os valores podem ser:
    - auto: mantém o align-itens do container
    - flex-start: início do container
    - flex-end: final do container
    - center: relativo ao centro de acordo com o eixo
    - stretch: ocupa todos os espaços relativo
    - baseline: utiliza a linha base da tipografia    