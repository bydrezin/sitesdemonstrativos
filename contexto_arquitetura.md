# Contexto e Arquitetura do Projeto: CreativzPet

## 📂 Estrutura de Pastas
Atualmente, a estrutura do projeto é extremamente simples e direta, típica de uma **Landing Page** estática de página única (Single Page):
- `/`: Diretório raiz do projeto.
- `index.html`: O único arquivo de código do projeto, contendo toda a estrutura, estilos e interatividade da página.
- `.git/`: Pasta de controle de versão (Git).

## 🛠️ Tecnologias Utilizadas
A aplicação foi construída utilizando tecnologias fundamentais da web moderna focadas em alta performance e simplicidade:
- **HTML5**: Fornece a estrutura semântica da página.
- **Tailwind CSS (via CDN)**: Framework de CSS utilitário usado para estilização, layouts responsivos e design moderno. O uso via CDN indica que não há um processo de build local configurado (como Node.js, Webpack ou Vite).
- **Vanilla JavaScript**: Utilizado diretamente dentro do arquivo `index.html` (no final do body) para lidar com interatividades simples, como a abertura do Menu Mobile e a lógica da Galeria de Imagens.
- **Google Fonts**: Utilização da fonte *Quicksand* para garantir uma tipografia amigável, arredondada e moderna.
- **Cloudinary**: Otimização e hospedagem de imagens. Os links das imagens no código apontam para `res.cloudinary.com`, garantindo um carregamento mais rápido e responsivo.

## 🎯 Objetivo Geral da Aplicação
O objetivo do projeto é servir como uma **Landing Page institucional e promocional** para a **CreativzPet**, uma clínica veterinária e pet shop focada no bem-estar animal. O foco principal é:
1. **Atrair e converter clientes:** Apresentando ofertas, descontos (promoção do 1º banho) e banners de produtos mais vendidos.
2. **Construir autoridade e confiança:** Através do design moderno, uso de prova social (depoimentos reais de clientes em um carrossel dinâmico) e grande ênfase no conceito de atendimento humanizado e ambiente *"Fear Free"* (Livre de Medo).
3. **Facilitar o contato e acesso:** Disponibilizando links rápidos para WhatsApp, Email e um mapa de localização integrado na seção final da página.

## 📐 Arquitetura
Por se tratar de um projeto centralizado em um arquivo único (`index.html`), não há separação arquitetural complexa de backend ou componentização via frameworks JS (como React/Vue). A arquitetura atual baseia-se puramente na divisão semântica do HTML por seções:
- **Topbar e Header:** Navegação, pesquisa e informações rápidas.
- **Hero Section:** Banner principal animado com chamada para ação (CTA).
- **Produtos/Banners:** Destaques de vendas e promoções encapsulados em contêineres de destaque.
- **Categorias:** Navegação iconográfica amigável.
- **Sobre Nós (Amor pelos Animais):** Explicação da filosofia do espaço com uma galeria de fotos integrada.
- **Prova Social:** Seção animada de marquee com os depoimentos.
- **FAQ:** Seção de dúvidas usando as tags HTML5 nativas `<details>` e `<summary>`.
- **Fale Conosco e Rodapé:** Informações finais de contato, iframe de mapa e links sociais.
