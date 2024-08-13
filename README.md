# Worst Generation Cup Ramdomizer

Conjunto de Scripts desenvolvidos por [Guilherme Arruda Pedroso](https://www.linkedin.com/in/guilherme-arruda-pedroso/).


### Contexto

---

Junto a um grupo de amigos decidimos que queriamos fazer um torneio do famoso [card game do One Piece](https://en.onepiece-cardgame.com/) onde seria valido utilizar apenas os líderes menos usados do jogo, como uma forma de explorar novas estratégias.

Com isso determinamos um formato de campeonato e foi decidido que os líderes de cada um seria utilizado de forma aleatória, portanto tive a ideia de desenvolver esse script que possibilita que esse sorteio seja efetuado de forma simples e imparcial.

Os dados iniciais foram obtidos através de votação dentro do nosso grupo de amigos, com isso o próprio script faz o rank daqueles que são considerados os melhos populares e sorteia entre os participantes de acordo com a modalidade escolhida.

---
### Instalação
---

__1. Clonar Repositório__
```
git clone https://github.com/GuiArrP/WGC.git
```

__2. Criar Ambiente de Desenvolvimento e Instalar Dependências__

Windows ([conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html)):
```
conda create -n WGC python=3.12.3
conda activate WGC
python -m pip install --upgrade pip wheel
python -m pip install -r requirements.txt
python -m pip install --upgrade notebook traitlets
```

Linux:
```
$ python -m venv --clear --copies WGC
$ source WGC/bin/activate
(notebooks) $ python -m pip install --upgrade pip wheel
(notebooks) $ python -m pip install -r requirements.txt
(notebooks) $ python -m pip install --upgrade notebook traitlets
```

