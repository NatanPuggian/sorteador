# Sorteador de Seleções — Copa do Mundo 2026

Sorteador web das 48 seleções classificadas para a Copa do Mundo FIFA 2026, com lógica de rodadas e containers por jogador.

## Funcionalidades

- **48 seleções oficiais** classificadas (fonte: fifa.com), com bandeiras locais (offline).
- **5 containers** (um por jogador: Dadau, Menezes, Erick, Mateus, Gianpaolo).
- **Lógica de rodadas:** cada sorteio cai no próximo container; ao completar os 5, avança a rodada (até a **Rodada 11**).
- **Regra de repetição por container:** uma seleção sorteada para um jogador nunca mais é sorteada para esse mesmo jogador, mas pode sair para outros.
- **Repetir último:** refaz o sorteio mais recente.
- **Reiniciar:** zera tudo de volta para a Rodada 1.
- Tema escuro/dourado com a imagem do troféu ao fundo.

## Uso

É um site estático — basta abrir `index.html` no navegador (precisa de internet apenas se a imagem de fundo não estiver na pasta `assets/`).

## Estrutura

- `index.html` — app completo (HTML + CSS + JS).
- `flags/` — bandeiras PNG das seleções.
- `assets/background.jpg` — imagem de fundo (troféu).
