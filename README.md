# 📋 README - Café & Bistrô Serenatto

## 🌟 Sobre o Projeto
Serenatto é um website responsivo para uma cafeteria/bistrô fictícia, desenvolvido como projeto prático do curso de Bootstrap 5 da Alura.

### ✨ Destaques:
✅ Design moderno e responsivo (mobile, tablet e desktop)  
✅ Modo noturno (alternância entre temas claro/escuro)  
✅ Navegação fluida com offcanvas menu (mobile)  
✅ Seções interativas:
- Cardápio com modais detalhados
- Formulário de contato responsivo
- Galeria de produtos  
✅ Efeitos visuais com Bootstrap (accordion, cards, modais)  

## 🛠️ Tecnologias Utilizadas
| Ferramenta | Descrição |
|------------|-------------|
| HTML5 | Estrutura semântica |
| Bootstrap | Framework CSS/JS |
| JavaScript | Interatividade |
| Google Fonts | Tipografia (Barlow) |

## 🎨 Design & Responsividade
### 📱 Mobile-First:
- Menu hambúrguer com offcanvas
- Cards em coluna única
- Formulário ocupando 100% da largura

### 💻 Desktop:
- Layout em grid (3 colunas para produtos)
- Formulário com 75% de largura (centralizado)
- Efeitos hover em cards

## 🚀 Funcionalidades Interativas
### Modo Noturno
- Alternância via toggle switch
- Aplicado em todo o site (`data-bs-theme`)

### Componentes Bootstrap:
- **Modais:** Detalhes dos produtos (cafés tradicionais/especiais)
- **Accordion:** Informações sobre serviços (Canvas)
- **Formulário:** Validação básica e campos flutuantes

### Galeria de Produtos:
- Grid responsivo (3 colunas em desktop → 1 em mobile)
- Modal com descrição detalhada ao clicar

## 📂 Estrutura de Arquivos
```
serenatto/  
├── assets/  
│   ├── favicon.png  
│   ├── logo.png  
│   ├── logo-mobile.png  
│   └── imagens (café, buffet, delivery, etc.)  
├── css/  
│   └── estilos.css          # Estilos personalizados  
├── js/  
│   └── script.js            # Lógica do modo noturno  
└── index.html               # Página principal  
```

## 🔧 Personalização
### Cores Principais (em `estilos.css`):
```css
:root {  
  --marrom-escuro: #372214;  
  --marrom-claro: #a25f4b;  
  --bege: #f5e7e0;  
}  
```
### Como alterar o tema:
- Modifique as variáveis CSS
- Ajuste as classes `botao-marrom` e `borda-marrom`

## 🌍 Acesso ao Projeto
🔗 **GitHub Pages:** [Link de Deploy](#) *(adicione seu link)*

### 📥 Clone:
```bash
git clone https://github.com/perazzavera/serenatto.git
```

## 📝 Créditos
- **Design:** Projeto fictício da Alura
- **Desenvolvimento:** Vera Perazza
- **Ícones:** Bootstrap Icons

## 📜 Licença
MIT License - Projeto educacional sem fins comerciais.

<p align="center"> ☕ Feito com carinho para amantes de café! </p>
