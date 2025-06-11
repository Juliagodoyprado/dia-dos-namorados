# Surpresa Romântica - Dia dos Namorados

Este projeto é uma página web responsiva e elegante, criada para celebrar o Dia dos Namorados com uma surpresa especial. A página apresenta um carrossel de imagens embutidas do Imgur, exibindo momentos especiais do casal, além de um texto romântico para tornar a experiência ainda mais memorável.

---

## Funcionalidades

- **Carrossel de imagens**: Exibe sete imagens em sequência, utilizando blocos de embed do Imgur para garantir que as imagens sejam carregadas diretamente do serviço.
- **Navegação automática**: O carrossel avança automaticamente a cada 4 segundos, proporcionando uma experiência dinâmica e fluida.
- **Controles manuais**: Botões "anterior" e "próximo" para controle manual da passagem das imagens, com foco e suporte para teclado (acessibilidade).
- **Design responsivo**: Layout otimizado para diferentes tamanhos de tela, garantindo boa aparência em desktops, tablets e dispositivos móveis.
- **Cabeçalho fixo**: Navegação com links e título fixo no topo, para fácil acesso e navegação.
- **Botão de retorno**: Permite o retorno à página inicial facilmente.

---

## Tecnologias Utilizadas

- HTML5 e CSS3 para construção e estilização da página.
- JavaScript para controle do carrossel e navegação das imagens.
- Fonte Google Fonts Poppins para tipografia moderna e limpa.
- Embeds do Imgur para exibição confiável das imagens do casal.

---

## Como Utilizar

1. Abra o arquivo `surprise.html` em seu navegador favorito.
2. A página exibirá o texto romântico com um carrossel de imagens.
3. O carrossel irá passar as imagens automaticamente a cada 4 segundos.
4. Use os botões laterais para avançar ou retroceder manualmente pelas imagens.
5. Para retornar à página inicial, clique no botão "Voltar".

---

## Personalização

- **Modificar imagens**  
  As imagens do carrossel são embutidas usando blocos do Imgur. Para trocar as imagens, atualize os blocos `<blockquote>` com o código embed correto dos seus posts do Imgur, mantendo a mesma estrutura HTML.

- **Ajustar intervalo de troca automática**  
  No script JavaScript, altere o valor `4000` (milissegundos) na função `setInterval` para aumentar ou diminuir o tempo de duração de cada imagem.

- **Estilização**  
  O estilo está presente dentro do bloco `<style>` na mesma página. Você pode alterar cores, tamanhos, fontes e espaçamentos conforme desejar.

---

## Acessibilidade

- Os botões do carrossel são acessíveis via teclado (Enter e Espaço).
- Uso de roles e labels ARIA para melhorar a navegação por leitores de tela.
- Layout responsivo para melhor experiência em múltiplos dispositivos.

---

## Créditos

- Imagens hospedadas em [Imgur](https://imgur.com).
- Fontes fornecidas por [Google Fonts](https://fonts.google.com/specimen/Poppins).

---

Caso tenha dúvidas ou queira suporte para customizações, sinta-se à vontade para abrir uma issue ou contato.
---
