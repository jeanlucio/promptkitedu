🔗 **Acesse a ferramenta online:**  
https://jeanlucio.github.io/promptkitedu/

# PromptKit EDU

O **PromptKit EDU** é uma ferramenta interativa desenvolvida para auxiliar professores na organização, criação e uso de *prompts* educacionais, especialmente para aplicações em **Moodle**, **IA generativa** e **produção de materiais didáticos**.

O sistema permite que qualquer docente mantenha sua própria biblioteca de prompts organizada por categorias, faça buscas, edite conteúdos, duplique itens, exporte backups, importe kits prontos e copie conteúdos com formatação especial para Moodle.

---

## 🧩 Recursos Principais

### ✅ Gerenciamento de Prompts
- Criar, editar, duplicar e excluir prompts.
- Sistema de categorias totalmente personalizável.
- Observações internas por prompt.
- Contador dinâmico de resultados após filtros.

### 🔎 Filtros e Organização
- Busca em tempo real.
- Filtragem por categorias.
- Ordenação A–Z e Z–A.
- Reorganização por arrastar e soltar (drag & drop).

### 💾 Salvamento e Backups
- Persistência automática via `localStorage`.
- Persistência permanente baseada em um identificador único do arquivo (`kpm-file-id`).
- Exportação e importação completas via JSON.
- Histórico de backups integrado.

### 🎨 Formatações Especiais para Moodle
O PromptKit EDU inclui conversores automáticos para:

- Padrão Moodle (HTML limpo e acessível)
- Padrão Gamificado
- Padrão Cards
- Padrão Cards Gamificado

Esses formatos são aplicados instantaneamente ao copiar o conteúdo.

### 📱 Otimização Mobile
- Interface adaptada para telas pequenas.
- Barra de ferramentas rolável.
- Botões reduzidos com ícones.
- Colapso inteligente do painel lateral.

### 🌙 Modo Claro/Escuro
Um clique alterna entre temas moderno claros e escuros.

---

## 🚀 Como Usar

1. Abra o arquivo `index.html` em qualquer navegador moderno.  
2. Adicione prompts, categorias e observações conforme necessário.  
3. Utilize filtros, buscas e ordenações para organizar seu conjunto.  
4. Exporte um arquivo `.json` quando quiser salvar um backup ou compartilhar.  
5. Importe esse `.json` para recuperar sua biblioteca em outro dispositivo ou momento.

---

## 🔒 Persistência Permanente

O sistema mantém os dados do usuário mesmo após fechar o navegador graças a um identificador único:

```html
<meta name="kpm-file-id" content="promptkit-edu-oficial">
```

Esse valor garante que os dados continuam vinculados à mesma instância do PromptKit, mesmo no GitHub Pages.

---

## 🛠 Tecnologias Utilizadas

- **HTML5**  
- **CSS3** (design responsivo + dark mode)  
- **JavaScript Vanilla**  
- `localStorage` para persistência  
- GitHub Pages para hospedagem  

Sem dependências externas, totalmente offline.

---

## 📦 Estrutura do Repositório

```
/
├── index.html   # Aplicação completa em arquivo único
└── README.md    # Documentação do projeto
```

---

## 🧑‍🏫 Público-Alvo

- Professores  
- Designers instrucionais  
- Coordenadores de EAD  
- Criadores de cursos no Moodle  
- Produção de materiais didáticos digitais  
- Pesquisadores de IA aplicada à educação  

---

## 📝 Licença

Projeto distribuído livremente para uso educacional.  
Você pode copiar, modificar e distribuir conforme necessário para fins pedagógicos.

---

## 👨‍💻 Autor

**Jean Lúcio Santos Evangelista**  
Instituto Federal do Sertão Pernambucano  
ORCID: https://orcid.org/0000-0001-6925-3311  
Lattes: http://lattes.cnpq.br/1677335727759690
