# 🍬 Catálogo Online

Catálogo interativo de produtos para atacado de doces, integrado ao Firebase Realtime Database e hospedado via GitHub Pages. Permite visualizar, buscar, adicionar, editar e excluir produtos em tempo real — de qualquer dispositivo, incluindo celular.

🔗 **Acesse online:** [lucas-lms.github.io/CatalogoBase](https://lucas-lms.github.io/CatalogoBase/)

---

## ✨ Funcionalidades

- 📦 **Catálogo completo** com mais de 120 produtos organizados em 10 categorias
- 🔍 **Busca em tempo real** por nome, marca ou observação
- 🗂️ **Filtro por categoria** via abas (Paçocas, Balas, Chicletes, Chocolates, etc.)
- 🔃 **Ordenação** por preço, preço/unidade ou nome
- ➕ **Adicionar produto** via modal com formulário completo
- ✏️ **Editar produto** diretamente pelo botão no card
- 🗑️ **Excluir produto** com confirmação
- ☁️ **Dados em nuvem** via Firebase — alterações aparecem em tempo real em todas as abas abertas
- 📱 **Design responsivo** — funciona bem em celular, tablet e desktop
- 🏷️ **Informações detalhadas:** preço total, preço/unidade, preço/kg, qtd. por caixa, tags, tabela nutricional e observações
- 🏪 **Seção de marcas** com histórico e origem de 14 marcas

---

## 🗂️ Categorias

| Ícone | Categoria |
|-------|-----------|
| 🥜 | Paçocas |
| 🍬 | Doces Típicos |
| 🌰 | Amendoim & Pé de Moleque |
| 🍌 | Bananadas |
| 🥨 | Biscoitos & Salgadinhos |
| 🍿 | Pipocas |
| 💬 | Chicletes & Pastilhas |
| 🍭 | Balas & Gomas |
| ☁️ | Marshmallows |
| 🎯 | Pirulitos |
| 🍫 | Chocolates & Importados |

---

## 🛠️ Tecnologias

- **HTML5 / CSS3 / JavaScript** — sem frameworks, sem build tools
- **Firebase Realtime Database** — armazenamento e sincronização em tempo real
- **GitHub Pages** — hospedagem gratuita do arquivo estático
- **Google Fonts** — tipografia Playfair Display + DM Sans

---

## 🚀 Como usar

### Adicionar um produto

1. Clique em **"+ Produto"** na barra superior
2. Preencha nome, marca, categoria e preço (obrigatórios)
3. Campos opcionais: qtd. por caixa, preço/un (auto-calculado), preço/kg, embalagem, tags, tabela nutricional e observações
4. Clique em **"Salvar"** — o produto aparece no catálogo imediatamente

### Editar um produto

1. Passe o mouse sobre qualquer card de produto
2. Clique no ícone **✎** no canto superior direito do card
3. Edite os campos desejados e clique em **"Salvar"**

### Excluir um produto

1. Abra o modal de edição do produto (ícone ✎)
2. Clique em **"🗑 Excluir"** e confirme

---

## 📁 Estrutura do repositório

```
CatalogoBase/
└── index.html        # Aplicação completa (HTML + CSS + JS em arquivo único)
└── README.md         # Este arquivo
```

## 📱 Preview

| Desktop | Mobile |
|---------|--------|
| Cards em grid multi-coluna, tabs fixas no topo | Coluna única, controles empilhados, botão de editar touch-friendly |

---

## 📄 Licença

Uso interno — Sem licença de redistribuição.
