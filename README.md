# ❤️ Gerador de QR Code Romântico — Pedido Especial

Uma aplicação web interativa e minimalista desenvolvida para gerar, personalizar, baixar em alta resolução ou imprimir cartões com QR Code para pedidos de namoro e surpresas românticas.

Por padrão, o gerador já aponta diretamente para:  
🔗 **`https://silaniiomr.github.io/pedido-namoro/`**

---

## ✨ Funcionalidades

- **Geração Instantânea e em Tempo Real:** O QR Code é atualizado automaticamente conforme você edita o link, as cores ou a mensagem.
- **Alta Tolerância a Erros (Nível H):** Configurado com 30% de redundância de dados (`QRCode.CorrectLevel.H`), garantindo leitura rápida e confiável pela câmera de qualquer smartphone — mesmo com o ícone de coração no centro.
- **Personalização Visual Completa:**
  - **Paleta de Alto Contraste:** Preto Clássico, Vermelho Paixão, Vinho e Rosa Escuro.
  - **Detalhe Central:** Opção de ativar ou desativar o ícone de coração centralizado.
  - **Estilos de Moldura:** *Cartão Romântico*, *Minimalista Clean* e *Estilo Polaroid*.
  - **Mensagens Personalizáveis:** Sugestões prontas ou campo livre para escrever sua própria frase.
- **Exportação em Alta Definição (PNG):** Renderização via HTML5 Canvas em escala $3\times$ ($1080\text{px}$ de largura), ideal para impressão nítida ou envio digital.
- **Modo de Impressão Otimizado:** Folha de estilos `@media print` dedicada que isola apenas o cartão na página, economizando tinta e papel.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & JavaScript (ES6+):** Estrutura semântica e manipulação dinâmica de Canvas 2D.
- **Tailwind CSS (via CDN):** Estilização responsiva, moderna e temática.
- **QRCode.js:** Biblioteca para geração da matriz do QR Code em alta precisão.
- **Lucide Icons:** Ícones vetoriais leves e elegantes.
- **Google Fonts:** Tipografia combinando *Playfair Display* (títulos e frases românticas) e *Inter* (interface).

---

## 🚀 Como Usar

Como o projeto foi construído em um **único arquivo autocontido** (`qrcode-pedido-namoro.html`), não há necessidade de instalar dependências ou configurar servidores:

1. **Baixe ou clone** o arquivo `qrcode-pedido-namoro.html` para o seu computador.
2. **Abra o arquivo** dando um duplo clique nele (ele abrirá diretamente no seu navegador padrão: Chrome, Edge, Safari, Firefox, etc.).
3. **Personalize** a cor, a moldura e a frase desejada na coluna à esquerda.
4. **Teste com seu celular** apontando a câmera para a prévia na tela antes de exportar.
5. Clique em **"Baixar QR Code (PNG)"** ou **"Imprimir Cartão"**.

---

## 💡 Dicas para a Surpresa

- **Tamanho mínimo na impressão:** Caso vá imprimir para colocar em um buquê, caixa de bombons ou envelope, garanta que o código tenha pelo menos **$3\text{ cm} \times 3\text{ cm}$**.
- **Escolha do papel:** Prefira papel sulfite comum ou papel fosco para evitar que o brilho da luz atrapalhe o foco da câmera do celular.

---

## 📄 Licença

Este projeto é de uso livre para fins pessoais e românticos. Boa sorte na surpresa! 🌹