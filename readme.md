# 🌟 Interactive 3D Card Gallery

Uma galeria responsiva e estilizada de cartões interativos com modelos 3D em `<model-viewer>`, efeitos visuais com CSS moderno e uso de variáveis CSS para escalabilidade e personalização.

## 📸 Preview

![preview](./preview.png)  
*A imagem acima é apenas ilustrativa. Experimente o projeto ao vivo para ver os modelos 3D em ação.*

## 🎯 Objetivo

Criar uma interface moderna e impactante, utilizando:
- Modelos 3D com `<model-viewer>`
- Animações suaves com `@keyframes`
- Máscaras com `mask` e `backdrop-filter`
- CSS responsivo com media queries
- Variáveis CSS para tema e escalabilidade
- Shadow Layering e efeito de *glassmorphism*

## 🧠 Tecnologias e recursos aplicados

| Tecnologia       | Finalidade                          |
|------------------|--------------------------------------|
| `HTML5`          | Estrutura dos cards e containers     |
| `CSS3` + SCSS    | Estilo visual, responsividade e lógica visual |
| `model-viewer`   | Renderização de modelos 3D interativos |
| `@import`        | Tipografia personalizada com a fonte *Satoshi* |
| `clip-path`      | Máscaras complexas para efeitos visuais |
| `box-shadow`     | Profundidade com sombras em camadas  |
| `flexbox`        | Alinhamento responsivo e fluido      |

## 🧩 Estrutura dos Cards

Cada `.card` possui:
- **Background customizável por variáveis** (`--clr`, `--fclr`)
- **Área de conteúdo** (`.content`) com título, parágrafo e opções
- **Área 3D** (`.model`) com o modelo em `<model-viewer>`
- **Camadas de vidro e blur** (`.glass`, `.gradient-blur`) para efeito de profundidade
- **Responsividade** com regras `@media` para esconder ou ajustar cards em diferentes tamanhos de tela

## ⚙️ Como rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/3d-card-gallery.git
cd 3d-card-gallery
Abra o index.html diretamente no navegador ou utilize uma extensão Live Server no VS Code.

Certifique-se de estar conectado à internet para carregar as fontes e os modelos 3D via CDN.

📦 Recursos externos
Fontes: Satoshi

Model-viewer: modelviewer.dev

Créditos de inspiração: Rafa3l no CodePen

📱 Responsividade
O layout adapta-se automaticamente em diferentes tamanhos de tela:

Telas < 700px: apenas dois cards são exibidos

Telas < 468px: apenas o card central é exibido

🧠 Aprendizados e técnicas abordadas
Manipulação avançada de sombras com múltiplas camadas

Uso de clip-path e mask para construção de efeitos gradientes com blur

Estratégias modernas de glassmorphism

Carregamento e animação de modelos 3D sem JavaScript adicional