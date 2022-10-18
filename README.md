### HTML5 e CSS3 parte 4: avançando no CSS
    Curso da formação: Iniciante em programação, Da Alura :p

#### Anotações da AULA 23:

###
    - Seletores avançados CSS:
        Seletor >, para acessar os filhos de determinado elemento. 
        Por exemplo, para acessar todos os p dentro de main:
        ...       
        main > p {
        }
        ...
        
        Seletor +, para acessar o primeiro irmão de determinado elemento.
        Por exemplo, para acessar o primeiro p após um img:
        ...
        img + p {
        }
        ...

        Seletor ~, para acessar todos os irmãos de determinado elemento. 
        Por exemplo, para acessar todos os p após um img:
        ...
        img ~ p {
        }
        ...

        Seletor not, para acessar os elementos, exceto algum. 
        Por exemplo, para acessar todos os p dentro de main, exceto o p que tem id missao:
        ...
        main p:not(#missao) {
        }
        ...

    Como fazer contas com CSS, com a propriedade calc.
