# EcoAventuras

Jogo educacional desenvolvido em **C** com a biblioteca **Allegro 5**. O jogador controla um sapo explorador e percorre cenários inspirados nos biomas brasileiros enquanto responde perguntas sobre fauna, flora, preservação e características ambientais.

<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/5deaeff0-9dcf-4a43-ae83-bb2ace30ad80" />


## Objetivo

O EcoAventuras busca ensinar educação ambiental por meio da exploração. Cada fase apresenta um cenário próprio, obstáculos, animais e perguntas relacionadas ao bioma visitado.

## Biomas presentes

- Amazônia
- Pantanal
- Pampa
- Caatinga

## Funcionalidades

- Seleção de mapas por bioma.
- Movimentação de personagem com animações.
- Perguntas de múltipla escolha distribuídas pelos cenários.
- Áreas bloqueadas e colisões específicas de cada mapa.
- Animais com movimentação própria, como bois e jacarés.
- Menu, configurações de som e telas informativas sobre os biomas.
- Imagens, fonte e trilha sonora integradas ao jogo.

## Tecnologias

- Linguagem C
- Allegro 5.2.9
- Allegro Image, Primitives, Audio, Acodec, Font e TTF
- Visual Studio com plataforma C++
- NuGet para os pacotes Allegro e AllegroDeps

## Executar no Windows

1. Clone o repositório:

```bash
git clone https://github.com/pedrobertanhi/Ecoaventuras.git
```

2. Abra `jogo-biomas-pi.sln` no Visual Studio.
3. Restaure os pacotes NuGet da solução.
4. Confirme se o projeto está usando o toolset compatível com o Visual Studio instalado.
5. Compile e execute mantendo as imagens, a fonte e o áudio nos caminhos esperados pelo projeto.

O arquivo de projeto atual usa o toolset `v143`, disponível no Visual Studio 2022, e o SDK do Windows 10.

## Estrutura principal

| Arquivo ou pasta | Responsabilidade |
| --- | --- |
| `main.c` | Fluxo principal, telas, biomas e perguntas |
| `movimento.c` | Movimento geral do personagem |
| `movimento_sapo.c` | Lógica e animação do sapo |
| `movimento_boi.c` | Movimento dos bois |
| `movimento_jacare.c` | Movimento dos jacarés |
| `recusos_allegro.c` | Inicialização e carregamento de recursos |
| `liberar_recursos.c` | Liberação dos recursos do Allegro |
| `*.png`, `*.jpg`, `*.jpeg` | Cenários, personagens e elementos visuais |
| `menu.ogg` | Áudio do menu |
| `jogo-biomas-pi.sln` | Solução do Visual Studio |

## Equipe

- Renan Horta
- Henrique Samecima
- Walison Moura
- Pedro Bertanhi
