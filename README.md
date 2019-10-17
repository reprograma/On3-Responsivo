# Conteúdo - Aula 19/10

Responsividade
1 [Layout Responsivo](#layoutResponsivo)
2 [Resolução de tela x Tamanho de tela](#resolucaoTamanho)
3 [Unidades de medida responsivas](#unidadesMedida)
4 [Breakpoints & Media Queries](#breakpointsMedia)
5 [Tipos de displays](#displays)
6 [Mobile First](#mobileFirst)

--- 

# Responsividade

<div id='layoutResponsivo'></div>

## Layout Responsivo 

Um layout responsivo é aquele que se adapta automaticamente aos diversos tamanhos de telas dos dispositivos no qual ele está sendo visualizado e é parte fundamento do conceito de **design responsivo**, que nada mais é do que a possibilidade de adaptação fluida de um site a diversos tamanhos de tela.

![gif-responsivo](https://media.giphy.com/media/b2CD0Qrq2ulwY/giphy.gif)

**Tipos de dispositivos:**
* Notebooks
* Tablets
* Celulares
* Desktops  
* Televisões

![many-devices](./imagens/many-devices.jpg)

**Alguns fundamentos para a construção de um layout responsivo são:**
* Redimensionar imagens automaticamente
* Simplificar e/ou ocultar elementos
* Adaptar o tamanho de botões e links para interfaces touch

**Vantagens:**
* Usabilidade (design adaptado para diversos formatos)
* Manuntenção (não precisa desenvolver outras versões)
* SEO Google (tudo em uma url só)

**Desvantagens:**
* Desenvolvimento apenas para os principais dispositivos do mercado
* Versões antigas de navegadores que não reconhecem a linguagem de adapatação
* Necessidade de uma pré construção da arquitetura do código e do layout
* Um pouco mais demorado para carregar 

---

<div id='resolucaoTamanho'></div>

## Resolução de tela x Tamanho de tela

**Resolução:** é a medida de definição de imagens digitais, que utiliza o **pixel** como unidade de medida.
**Tamanho de tela:** tamanho físico da tela, normalmente medido em polegadas.

* Pixels por polegada: PPI - __**P**ixels **P**er **I**nch__ para monitores e telas

![comparativa-resolucao](./imagens/comparativa-resolucao.jpg)

É fundamental termos em mente que a resolução é determinada pelo tamanho da tela (expresso pela sua altura e largura) mais a quantidade de pixels nela inserida.

Dessa forma, olhando simplesmente para o tamanho (largura x altura) não podemos afirmar que esse possui alta ou baixa resolução. A quantidade de pixels contidas nele, é que dirá se o mesmo possui alta ou baixa resolução.

Podemos ter um tamanho de tela com dimensões grandes porém com poucos pixels. O inverso também é possível, um tamanho com dimensões pequenas porém com muitos pixels. Assim, dispositivos que possuem o mesmo tamanho nem sempre possuem uma mesma resolução. 

---

<div id='unidadesMedida'></div>

## Unidades de medida responsivas

**Medidas absolutas:**

Essas são as mais comuns que vemos no dia a dia. São medidas que não estão referenciadas a qualquer outra unidade, ou seja, não dependem de um valor de referência.

Essas medidas são fixas e não mudam de acordo com as especificações do dispositivo.

__Quais são:__ pixels (px), points (pt), inches/polegadas (in), centímetro (cm), milímetro (mm) e paica (pc)

* 96px = 1 in = 2,54cm = 25,4mm = 72pt = 6pc

**Medidas relativas:** 

Essas são as que normalmente não estamos habituados. Essas medidas são calculadas tendo como base uma outra unidade de medida pré definida.

Devido ao fato de que essas medidas serem calculadas pelo browser baseando-se em outra unidade, elas tendem a ser bastantes flexíveis. Ou seja, podemos ter resultados diferentes de acordo com o tamanho de tela. 

__Quais são:__

* em

    **EM** é uma unidade de medida tipográfica. Para entender sua aplicação, vamos utilizar o exemplo abaixo onde foi definido um tamanho de fonte no elemento `<div>`, o valor de **em** declarado em qualquer elemento-filho dentro de `<div>` será igual a: **o valor declarado no elemento-filho * o valor declarado no elemento pai**. 

    Nesse caso: **1.2(em) * 14px = 16.8px**

    ![unidade-em](./imagens/unidade-em.jpg)

    Entretanto, o que acontece quando se tem um elemento com valor **em** dentro de outro elemento com valor **em**?

    ![unidade-em-dentro-de-em](./imagens/unidade-em-dentro-de-em.jpg)

* rem
* porcentagem %
* ex 
* ch
* vh 
* vw
* vmin 
* vmax

---

<div id='breakpointsMedia'></div>

## Breakpoints e Media Queries

---

<div id='displays'></div>

## Tipos de displays
### Flex
### Grid

---

<div id='mobileFirst'></div>

## Mobile First


