# Gerador de QR Code Profissional

Aplicação web leve e responsiva em HTML5, CSS (Tailwind CSS) e JavaScript puro para criar, personalizar, imprimir e baixar **QR Codes em alta resolução (1080px de largura)** com correção de erros **Nível H (30% de redundância)**.

## Funcionalidades

- **Geração em tempo real:** Atualiza o QR Code automaticamente conforme o usuário digita uma URL, link ou texto.
- **Paleta de cores de alto contraste:** Opções pré-definidas (*Preto Clássico*, *Azul Royal*, *Verde Esmeralda* e *Grafite*) pensadas para leitura rápida por câmeras.
- **Ícone central opcional (Nível H):** Insere um ícone de link no centro do código mantendo margem de segurança para leitura.
- **Estilos de moldura e rótulos:** Alterna entre *Cartão Moderno*, *Minimalista Clean* e *Placa / Display*, com sugestões rápidas (*Escaneie o QR Code*, *Acesse nosso site*, *Aponte a câmera aqui*, *Conecte-se ao Wi-Fi*, *Sem texto*) ou texto personalizado de até 48 caracteres.
- **Exportação PNG em alta resolução:** Gera um cartão completo renderizado em `<canvas>` (`1080px` de largura) pronto para impressão ou compartilhamento.
- **Impressão direta:** Layout adaptado com `@media print` para imprimir apenas a área do cartão.

## Tecnologias utilizadas

- **HTML5 & CSS3** com **Tailwind CSS** (via CDN)
- **JavaScript (ES6+)** com **HTML5 Canvas**
- **QRCode.js** para geração da matriz do QR Code
- **Lucide Icons** para ícones da interface

## Como executar

1. Salve o código da aplicação como `index.html`.
2. Abra o arquivo `index.html` diretamente em qualquer navegador moderno (Chrome, Edge, Firefox, Safari) ou sirva via servidor HTTP local / hospedagem estática (por exemplo, cPanel, GitHub Pages, Netlify ou Vercel).
3. Não requer instalação de dependências nem build backend.

## Boas práticas de leitura e impressão

- **Teste prévio:** Escaneie a prévia na tela com a câmera do celular antes de imprimir ou publicar.
- **Tamanho mínimo:** Para cartões, folhetos ou balcões, utilize ao menos **2,5 cm × 2,5 cm**.
- **Superfície:** Prefira papel fosco ou evite brilho excessivo sobre o código para não dificultar o foco da câmera.