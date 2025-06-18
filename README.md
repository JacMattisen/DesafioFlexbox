## 🎯 Desafio Flexbox - DIO

Este projeto é um clone simplificado da interface do YouTube, criado com o objetivo principal de praticar Flexbox no CSS. A estrutura HTML foi cuidadosamente organizada para representar diferentes seções da interface: barra de navegação, conteúdo principal (vídeo), e uma seção lateral com vídeos recomendados.

🧱 Estrutura do Projeto
📁 Arquivos principais
index.html: Estrutura do layout da página.

styles.css: Estilos aplicados com foco em Flexbox.

🔍 Componentes da Página
1. 🧭 Barra de Navegação (<nav class="navbar">)
Dividida em três seções com uso de Flexbox:

Esquerda: Ícone do menu e logo do YouTube.

Centro: Campo de busca com botão.

Direita: Ícones de vídeo, notificação e avatar do usuário.

2. 🎥 Conteúdo Principal (<section class="container">)
📹 Parte Esquerda (<div class="container-left">)
Vídeo incorporado via iframe.

Título, informações do canal, botões de interação (curtir, compartilhar, baixar).

Descrição e links úteis.

📺 Parte Direita (<aside class="container-right">)
Lista de vídeos recomendados com miniatura e detalhes.

💡 Objetivo Principal
✅ Utilização do Flexbox para criar um layout responsivo e bem distribuído!

Todas as principais seções (navegação, corpo da página, vídeo e colunas laterais) foram estruturadas com Flexbox, permitindo uma distribuição fluida e organizada dos elementos.

🛠️ Tecnologias Utilizadas
HTML5

CSS3 (com Flexbox)

Font Awesome (ícones)

📸 Pré-visualização
Layout responsivo que simula uma experiência de navegação semelhante ao YouTube, com destaque para:

Alinhamento horizontal e vertical com Flexbox.

Adaptação de conteúdo lateral.

Estilização moderna e intuitiva.

✨ Resultado Esperado
Criar uma página que:

Replique de forma simplificada o layout do YouTube.

Utilize Flexbox como base principal de posicionamento.

Organize o conteúdo de forma clara e responsiva.

## 📱 Melhoria de Responsividade

Para garantir uma boa visualização também em **telas menores** (janelas minimizadas no PC), foi adicionada uma media query:

### ✅ Media Query: `@media (max-width: 1024px)`  
Aplica-se a janelas minimizadas em desktops e notebooks

📌 Considerações Finais
✅ O uso de Flexbox garantiu uma estrutura clara, adaptável e com excelente organização dos elementos.

🚀 A adição das media queries tornou o layout totalmente responsivo, funcionando perfeitamente tanto em telas grandes, quanto em telas menores como notebooks em modo janela.
