# Pesquisa-Conceitos-de-Imagem

Gustavo da Silva Rezende e Daniel Ryu

## Imagem Digital: Definição.

#### A **Imagem Digital** é a representação de uma imagem bidimensional na forma de números binários usando um conjunto de elementos discretos e de tamanhos finitos, chamados de pixels, colocados em um arranjo bidimensional.

## O que é um pixel?

#### Pixel é a menor unidade de uma imagem digital, independente de sua fonte. Se você pegar uma foto e dar zoom, você verá uma série de quadradinhos que a compõem. Cada um desses pontos luminosos é um pixel. São milhões ou milhares deles. Cada pixel é baseado nas três cores básicas do padrão RGB: vermelho, verde e azul. Monitores convencionais trabalham em uma profundidade de 8 bits. Isso significa que cada uma das três cores básicas possui 256 tonalidades.

## Tipos de Imagens Digitais.

#### Há dois tipos fundamentais de imagem digital. Uma é do tipo rastreio (raster) e outra do tipo vetorial. Uma imagem digital do tipo raster, é aquela que em algum momento apresenta uma correspondência bit-a-bit entre os pontos da imagem raster e os pontos da imagem reproduzida na tela de um monitor. A imagem vetorial não é reproduzida necessariamente por aproximação de pontos, antes era destinada a ser reproduzida por plotters de traçagem que reproduziam a imagem por deslocamento de canetas-tinteiro.

<img src="img/raster.jpg" width="200" height="200">               <img src="img/vector.jpg" width="200" height="200">

## Como funciona as cores na arte digital:

#### A fonte de luz de um monitor ou tela pode criar qualquer cor que você possa imaginar com a combinação de diferentes tonalidades de vermelho, verde e azul. Os nossos olhos são capazes de identificar cerca de 1 milhão de cores que terão suas variações de ondas percebidas pelo cérebro. Entretanto, o que é mais curioso é que essa enorme quantidade tons deriva de apenas 12 classificadas como primárias, secundárias e terciárias. Elas fazem parte do círculo cromático.

## Densidade das cores através do Bits:

#### Pegando um exemplo do modo RGB: o sensor da câmera capta a luz, separa os canais vermelho, verde e azul e traduz a luminância de cada um que chegou até ele para código binário (zeros e uns). É a quantidade de código binário gerado pelo sensor é a que vai determinar a variação de tonalidades que aquele arquivo tem.

<img src="img/colorCode.png" width="155" height="200">

#### Agora, se a cor vermelha pudesse ser representada por um código binário de 2 bits, isto é, duas unidades (0-0, 0-1,1-0 ou 1-1), você teria quatro tonalidades de vermelho, sendo 0-0 a ausência dele e 1-1 a presença total, e os demais seriam outras variações da cor.

## Modelos de cores em Imagens Digitais:

#### 1. RGB: O modelo de cores RGB é um sistema de cores aditivo, em que as cores são formadas adicionando luz a cada uma das cores intervenientes no processo, inspirado na teoria de visão colorida tricromática e tem como base as cores: vermelho, verde e azul. Este modelo pode produzir até 16,7 milhões de cores. Este é o modelo mais usado e conhecido.

#### 2. CMKY: O modelo CMYK tem como base as cores primárias (azul ciano, magenta, amarelo) e o preto. É usado geralmente em impressoras e fotocopiadoras. Neste modelo cada cor é descrita com uma percentagem (de 0% a 100%), sendo que quanto maior for a percentagem, mais escura a cor será. Este modelo é um modelo subtractivo de cores pois cria cores absorvendo luz.

#### 3. LAB: O modelo LAB é um modelo matemático que foi criado em 1931 pela CIE (La Commision Internationale de L’Eclairage)  e foi inspirado na forma como o olho humano percepciona as cores. Em 1976, o modelo foi melhorado de forma a garantir cores mais consistentes, independentemente das características do hardware. Este modelo funciona através de um canal de luminosidade e de dois canais de cor (a e b).
