# Rodovia do Deserto

Jogo de corrida em pseudo-3D que roda direto no navegador. Um único arquivo (`index.html`), sem dependências e sem etapa de build.

Desvie do tráfego, evite os obstáculos e cruze a linha de chegada em cada uma das 4 fases. Você tem 3 vidas por fase e, se bater a terceira vez, tenta a fase de novo. O cronômetro mede o seu tempo e o melhor tempo de cada fase fica salvo no navegador.

## Fases

| Fase | Cenário | Voltas | Tráfego |
|---|---|---|---|
| 1 | Deserto | 3 | leve |
| 2 | Pradaria | 4 | médio |
| 3 | Neve | 4 | intenso |
| 4 | Noite | 5 | muito intenso, curvas mais fechadas |

## Controles

| Ação | Teclado | Celular |
|---|---|---|
| Acelerar | ↑ ou W | botão **Acelerar** |
| Frear | ↓, S ou Espaço | botão **Freio** |
| Esquerda / direita | ← → ou A D | botões ◀ ▶ |
| Pausar | P | — |
| Som | M | botão **Som** |

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub.
2. Envie `index.html` e `README.md` para a branch `main`.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`, e clique em **Save**.
5. Depois de alguns minutos, o jogo estará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Rodar localmente

Abra o `index.html` em qualquer navegador moderno.
