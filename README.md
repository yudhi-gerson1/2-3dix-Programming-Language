# 2&3Dix
*Se não souber desenhar algo, programe ele.*

```text
2&3Dix: Comandos 2D
Formas: Objetos 2d para fazer artes ou animações. Exemplo de Síntaxe:
forma: 
  >> Suas propriedades aqui...
- circle: Cria um objeto redondo, útil para fazer olhos de um personagem.
- square: Cria um quadrado na tela.
- triangle: Cria um triangulo.
- star: Cria uma estrela.
- line: Cria uma linha.
- text = "Seu texto": Cria um texto.

Propriedades: A definição do seu objeto. Exemplo de Síntaxe:
square:
  propriedade = tipo
- size: o tamanho do seu objeto. 
Exemplo 1: size = 50px (o padrão)
Exemplo 2: size = 30px 20px (30px de largura, 20px de altura)
Exemplo 3: size = standard (o padrão é 50px)
Funciona para todos os objetos menos o line.
- position: A posição do seu objeto. O centro é 0px 0px.
Exemplo 1: position = 15px 20px (15px para direita, 20px para cima)
Exemplo 2: position = center (0px 0px)
Para as linhas, tem que definir a posição de dois pontos, fazemos assim:
position = 15px 30px, 20px 15px.
- color: A cor do seu objeto. Pode ser com as palavras reservadas (red, blue, etc.) ou com hexadecimal.
Exemplo 1: color = red
Exemplo 2: color = #FF0000
- thickness: A espessura da linha (só pode ser usado para line)
Exemplo 1: thickness = 15px.
Exemplo 2: thickness = standard (o padrão é 12px).
- zindex: Define se o objeto está na frente ou atrás.
Exemplo 1: zindex = standard (Define o zindex como 0)
Exemplo 2: zindex = 3
>>: Um comentário em 2&3Dix.
Exemplo: >> Boo!

Quais propriedades cada objeto suporta:
Objetos comuns: size, position, color, zindex
Texto: size, position, color, zindex, thickness
Linha: position, color, zindex, thickness
