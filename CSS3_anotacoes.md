curso web completo 

CSS

INLINE

OBS: ELEMENTOS DO TIPO BLOCK (EX DIV), OCUPAM TODO O ESPAÇO DA TELA;

AULA 44 - 

ELEMENTOS BLOCO

- Inline:

    Um elemento a frente do outro
    exemplos: <a> <span> <img>

- Block:
    Ocupam todo o espaço horizontal da tela
    exemplos: <h1> <p> <table>

- Inline-block:
    O elemento tem a largura definida baseada no seu conteúdo
    mas os itens ficam um abaixo do outro
    exemplos: <!-- display: inline-block -->


_______________________________-

SELETORES

Seletor Universal - Aplica-se em todos os elementos no documento.
Exemplo: *{} Seleciona todos os elementos da página.

Seletor de Texto - Seleciona um elemento cujo atributo id tem o valor especificado após o símbolo da cerquilha ou jogo da vela.
Exemplos: h1, h2, h3 {} Seleciona os elementos <h1>, <h2>, <h3>

Seletor de Classe - Seleciona um elemento cujo atributo class tem o valor especificado depois de pronto.
Exemplo: .verde{} Seleciona qualquer elemento cujo atributo class tem o valor "verde" p.verde{} Seleciona somente elemento <p> cujo atributo class tem o valor "verde".

Seletor de ID - Seleciona um elemento cujo atributo id tem o valor específicado após o símbolo da cerquilha ou jogo da velha.
Exemplo: #cabecalho{} Seleciona o elemento cujo atributo id tem o valor "cabecalho"

Seletor de Filho - Seleciona um elemento que é filho direto de outro.
Exemplo: li>a {} Seleciona quaisquer elementos <a> que são filhos de um elemento <li> (mas não outros elementos )

SELETOR DE DESCENDENTE - Seleciona um elemento que é descendente de outro elemento especificado (e não apenas filho direto desse elemento) 
EXEMPLO: p a {}
    Seleciona quaisquer elementos <a> que residem dentro de um elemento <p>, mesmo se houver outros elementos aninhados entre eles.

SELETOR DE IRMÃO ADJACENTE - Seleciona um elemento que é o irmão próximo de outro. 
EXEMPLO: h1 + p {} --- 
    Seleciona o primeiro elemento <p> depois de qualquer elemento <h1> (mas não outros elementos <p>)

SELETOR DE IRMÃO GERAL - Seleciona um elemento que é um irmão de outro, embora ele não precise ser o elemento diretamente precedente.
EXEMPLO: h1-p {}
    Se houvesse dois elementos <p> que fossem irmãos de um elemento <h1>, essa regra se aplicaria aos dois.