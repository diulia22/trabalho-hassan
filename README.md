
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c06499f5-9ae6-41b2-ae76-918aaabb77f1" />
📚 BibliotecaJS - Sistema de Gerenciamento de Acervo
https://img.shields.io/badge/Status-Conclu%C3%ADdo-success
https://img.shields.io/badge/Version-2.0-blue
https://img.shields.io/badge/License-MIT-green
Sistema moderno de gerenciamento de biblioteca com interface escura elegante e funcionalidades completas para controle de acervo literário.
https://via.placeholder.com/800x400/1a1a2e/ffffff?text=BibliotecaJS+-+Sistema+Moderno
✨ Funcionalidades Destacadas
🎨 Interface Dark Mode - Design moderno com tema escuro e efeitos de glassmorphism
📱 Responsividade Total - Adaptado para desktop, tablet e mobile
💾 Duplo Sistema de Armazenamento
JSON para versão Node.js
LocalStorage para versão navegador
🔍 Relatórios Detalhados - Visualização completa do acervo com totais
⚡ Performance Otimizada - Animações suaves e carregamento rápido
🛠️ Tecnologias Utilizadas
Frontend: HTML5, CSS3 (CSS Grid, Flexbox, Variáveis CSS)
Backend: JavaScript (ES6+), Node.js
Armazenamento: JSON File System, LocalStorage API
Dependências: Prompt-sync (para CLI)
🚀 Como ExecutarVersão Web (Navegador)
bash
Copy
Download
# Clone o repositório
git clone https://github.com/seu-usuario/bibliotecajs.git

# Acesse a pasta do projeto
cd bibliotecajs

# Abra o arquivo index.html no navegador
# ou utilize um servidor local:
python -m http.server 8000
# depois acesse: http://localhost:8000
Versão CLI (Node.js)
bash
Copy
Download
# Instale as dependências
npm install prompt-sync

# Execute o sistema
node main.js
📦 Estrutura do Projeto
text
Copy
Download
bibliotecajs/
├── 📄 index.html          # Interface principal
├── 🎨 style.css           # Estilos modernos (tema escuro)
├── ⚙️ main.js             # Sistema principal (CLI)
├── 📊 biblioteca.json     # Banco de dados
├── 📂 funcoes/
│   ├── 💾 armazenamento.js    # Gerenciamento de dados
│   ├── ➕ cadastrarLivros.js  # Cadastro de livros
│   ├── 📋 listarLivros.js    # Listagem do acervo
│   ├── 🧮 calcularTotal.js   # Cálculos de inventory
│   ├── 📈 gerarRelatorio.js  # Relatórios detalhados
│   └── 🗑️ excluirLivros.js   # Gestão de remoções
└── 📖 README.md
🎯 Funcionalidades Detalhadas1. Gestão de Livros
Cadastro completo (título, autor, ano, quantidade)
Edição de registros existentes
Exclusão segura com confirmação
Validação de dados de entrada
2. Relatórios e Visualizações
Listagem completa do acervo
Relatório detalhado com estatísticas
Cálculo automático de totais
Busca e filtros (em desenvolvimento)
3. Sistema de Armazenamento
Persistência em arquivo JSON (Node.js)
LocalStorage para versão browser
Backup e recuperação de dados
Integridade de dados garantida
🎨 Design Features
Tema Escuro Moderno - Interface com cores #1a1a2e, #16213e, #0f3460
Efeito Glassmorphism - Cards com efeito de vidro translúcido
Animações Suaves - Transições e hover effects
Tipografia Elegante - Fontes Poppins e Fira Code
Responsividade - Layout adaptável para todos os dispositivos
🔧 Personalização
O sistema permite fácil personalização através das variáveis CSS:
css
Copy
Download
:root {
    --bg-primary: #1a1a2e;
    --bg-secondary: #16213e;
    --accent-primary: #e94560;
    /* Adicione suas cores aqui */
}
📋 Regras de Negócio
✅ Validação de campos obrigatórios
✅ Impedimento de exclusão de acervo vazio
✅ Alertas de estoque alto (>20 unidades)
✅ Persistência automática de alterações
✅ Interface intuitiva para não-usuários técnicos
🌟 Próximas Atualizações
Sistema de empréstimos de livros
Módulo de reservas online
Relatórios em PDF
Sistema de usuários e permissões
