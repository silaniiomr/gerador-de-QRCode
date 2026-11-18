# ❤️ Gerador de QR Code Romântico

Uma aplicação web interativa, elegante e minimalista desenvolvida para gerar, personalizar, baixar em alta resolução ou imprimir cartões com QR Code para pedidos de namoro e surpresas românticas.

---

## ✨ Funcionalidades

- **Geração Instantânea e em Tempo Real:** O QR Code é atualizado dinamicamente conforme você edita o link, as cores ou a mensagem.
- **Alta Tolerância a Erros (Nível H):** Configurado com 30% de redundância de dados (`QRCode.CorrectLevel.H`), garantindo leitura rápida e confiável pela câmera de qualquer smartphone — mesmo com o ícone de coração no centro.
- **Personalização Visual Completa:**
  - **Paleta de Cores de Alto Contraste:** *Preto Clássico*, *Vermelho Paixão*, *Vinho Elegante* e *Rosa Escuro*.
  - **Detalhe Central:** Opção de ativar ou desativar o ícone de coração estilizado no centro do QR Code.
  - **Estilos de Moldura:** *Cartão Romântico* (com ornamentos), *Minimalista Clean* e *Estilo Polaroid*.
  - **Mensagens Personalizáveis:** Sugestões prontas com um clique ou campo de texto livre para escrever sua própria frase.
- **Exportação em Alta Definição (PNG):** Renderização avançada via HTML5 Canvas em escala $3\times$ (alta nitidez e proporção ideal para impressão), combinando perfeitamente a moldura, o QR Code e a frase romântica.
- **Modo de Impressão Otimizado:** Folha de estilos `@media print` dedicada que isola e centraliza apenas o cartão na página, economizando tinta e papel.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & JavaScript (ES6+):** Estrutura semântica e manipulação avançada de Canvas 2D.
- **Tailwind CSS (via CDN):** Estilização responsiva, moderna e paleta de cores temática.
- **QRCode.js:** Biblioteca confiável para geração da matriz do QR Code em alta precisão.
- **Lucide Icons:** Ícones vetoriais leves e elegantes.
- **Google Fonts:** Tipografia combinando *Playfair Display* (títulos e frases românticas) e *Inter* (interface de usuário).

---

## 🚀 Como Usar

Como o projeto foi construído em um **único arquivo autocontido** (`index.html`), não há necessidade de instalar dependências complexas ou configurar servidores locais:

1. **Baixe ou clone** o arquivo `index.html` para o seu computador.
2. **Abra o arquivo** dando um duplo clique nele (ele abrirá diretamente no seu navegador padrão: Chrome, Edge, Safari, Firefox, etc.).
3. **Personalize** a cor, o estilo da moldura, o link de destino e a frase desejada diretamente nos controles da interface.
4. **Teste com seu celular** apontando a câmera para a prévia na tela antes de exportar.
5. Clique em **"Baixar QR Code (PNG)"** para salvar a imagem final ou em **"Imprimir Cartão"**.

---

## 💡 Dicas para a Surpresa

- **Tamanho mínimo na impressão:** Caso vá imprimir para colocar em um buquê, caixa de bombons ou envelope, garanta que o código impresso tenha pelo menos **$3\text{ cm} \times 3\text{ cm}$**.
- **Escolha do papel:** Prefira papel sulfite comum ou papel fosco para evitar que o brilho da luz reflita e atrapalhe o foco da câmera do celular.

---

## 📄 Licença

Este projeto é de uso livre para fins pessoais e românticos. Boa sorte na surpresa! 🌹