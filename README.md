Portal de Notícias

Um site de notícias moderno, elegante e responsivo, construído em HTML e CSS puro.

✅ Visão Geral

Este projeto apresenta um portal de notícias fictício que mostra como estruturar uma página com destaques, seções temáticas e layout em grade (grid). A ideia é combinar um design sofisticado com tipografia limpa, cores sóbrias e boa hierarquia visual.

🔍 Funcionalidades

Layout responsivo, com contêiner centralizado (.container) e uso de CSS Grid.

Seção de destaques (#featured) com imagem grande + cards menores.

Seção temática de inteligência artificial (#ai) com artigos em formato “imagem + texto”.

Barra de navegação principal (#primary) e secundária (#secondary).

Uso de variáveis CSS (:root) para manter estilo consistente (cores, fontes, etc).

Cartões de conteúdo (.card) com efeito de sobreposição via pseudo-elementos (::before) para dar profundidade visual.

Acessibilidade básica: atributos alt em imagens, semântica com section, article, figure, figcaption.

🛠️ Tecnologias Utilizadas

HTML5

CSS3 (variáveis CSS, Grid, Flexbox)

Fontes do Google Fonts: Inter Tight, Alice, Elms Sans, Roboto

Estrutura de pastas simples:

assets/      → ícones, imagens  
styles/      → arquivo CSS principal  
index.html   → página principal  

🚀 Como Rodar

Clone este repositório:

git clone https://github.com/Gab-byt/Portal-de-Noticias.git


Entre na pasta do projeto:

cd Portal-de-Noticias


Abra o arquivo index.html no seu navegador de preferência.
(Não há backend — é front-end estático.)

🎨 Personalização

Para trocar a paleta de cores, edite as variáveis em :root no CSS (styles/index.css).

Para ajustar o layout ou adicionar cards, basta editar o HTML conforme o padrão existente.

Quer adicionar responsividade maior? Use media queries no CSS para adaptar grelhas e tamanhos de imagem.

🔧 Próximos Passos / Melhorias Possíveis

Tornar o site 100% responsivo para dispositivos móveis.

Implementar lazy-loading de imagens para melhorar performance.

Adicionar interatividade com JavaScript (menu colapsável, filtro de categorias, etc).

Inserir animações sutis (hover nos cards, transições de imagem, etc).

Integrar com CMS ou API para conteúdo dinâmico.

📄 Licença

Este projeto está sob a licença MIT — sinta-se livre para usar, modificar e distribuir como quiseres.
