# Jarvis do Dia (versão celular)

App que você instala na tela inicial do celular. Mostra clima de Varginha-MG, dólar, euro, Bitcoin, Ethereum
e notícias de tecnologia, jogos, economia e do presidente/governo federal.

## Como colocar no ar (grátis, uns 2 minutos)

PWA precisa estar em um endereço na internet (https). O jeito mais fácil:

1. No computador, abra https://app.netlify.com/drop
2. Arraste a pasta `jarvis-celular` inteira para a página
3. Ele gera um link do tipo `https://nome-aleatorio.netlify.app`. Abra esse link no celular.

(Também funciona no GitHub Pages ou no Cloudflare Pages.)

## Como instalar no celular

- Android (Chrome): menu ⋮ → "Instalar app" ou "Adicionar à tela inicial"
- iPhone (Safari): botão Compartilhar → "Adicionar à Tela de Início"

## Como usar

- Abra pelo ícone: ele já atualiza sozinho se os dados estiverem velhos
- Toque na bolinha azul para atualizar na hora
- Toque nas abas para trocar o tema das notícias
- O topo mostra "Resumo da manhã" ou "Resumo do anoitecer" conforme o horário e o pôr do sol real de Varginha

## Personalizar

No `index.html`, procure o bloco `CFG` no começo do script: dá para trocar cidade, temas de notícia e moedas.
