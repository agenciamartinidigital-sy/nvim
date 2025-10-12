# nvim


⚡ Neovim Config - Agência Martini Digital

Configuração personalizada do Neovim usando Vimscript (init.vim).  
Feita para oferecer praticidade, produtividade e um fluxo de trabalho simples e direto.

---

📦 Requisitos

Antes de instalar, verifique se você tem:

- Neovim >= 0.5
- Git
- Node.js
- Ripgrep

---

⚙️ Instalação

`bash
git clone https://github.com/agenciamartinidigital-sy/nvim ~/.config/nvim
`

Abra o Neovim e rode:

`vim
:PlugInstall
`

> Obs: Este setup usa vim-plug como gerenciador de plugins.  
> Caso não tenha, instale seguindo as instruções: vim-plug

---

🗂 Estrutura

`text
nvim/
├── init.vim        # Arquivo principal de configuração
├── plug.vim        # Lista de plugins
└── README.md
`

---

✨ Funcionalidades

- 🎨 Tema customizado com ícones
- 🔍 Busca rápida com fzf
- 🧠 Autocompletion com coc.nvim
- 📜 Syntax highlight aprimorado
- 🔄 Integração com Git via vim-fugitive
- 🖥 Terminal integrado

---

⌨️ Atalhos Principais

📂 Arquivos e Navegação

| Atalho         | Ação                                |
|----------------|-------------------------------------|
| :w           | Salvar arquivo                      |
| :q           | Fechar arquivo                      |
| :wq          | Salvar e sair                       |
| :q!          | Sair sem salvar                     |
| :bn / :bp  | Próximo / Anterior buffer           |
| :bd          | Fechar buffer atual                 |
| Ctrl + p     | Buscar arquivos (fzf)               |
| Ctrl + n     | Abrir/fechar NERDTree               |

🔍 Busca e Substituição

| Atalho         | Ação                                |
|----------------|-------------------------------------|
| /palavra     | Buscar palavra                      |
| n / N      | Próxima / Anterior ocorrência       |
| :%s/a/b/g    | Substituir todas as ocorrências     |
| :noh         | Limpar highlights da busca          |

🧠 LSP / Autocompletion (coc.nvim)

| Atalho         | Ação                                |
|----------------|-------------------------------------|
| gd           | Ir para definição                   |
| gr           | Listar referências                  |
| gi           | Ir para implementação               |
| K            | Mostrar documentação                |
| [d / ]d    | Navegar entre erros                 |
| <Tab>        | Autocompletar sugestão              |

🎨 Edição e Produtividade

| Atalho         | Ação                                |
|----------------|-------------------------------------|
| gcc          | Comentar linha (vim-commentary)     |
| gc + movimento | Comentar bloco                   |
| yy / dd    | Copiar / Recortar linha             |
| p            | Colar                               |
| u / Ctrl + r | Desfazer / Refazer               |
| >> / <<    | Indentar / Desindentar              |

🔄 Git (vim-fugitive)

| Atalho         | Ação                                |
|----------------|-------------------------------------|
| :G           | Status do Git                       |
| :Gdiffsplit  | Diff lado a lado                    |
| :Gblame      | Mostrar blame                       |
| :Gpush       | Push                                |
| :Gpull       | Pull                                |

🖥 Terminal

| Atalho               | Ação                           |
|----------------------|--------------------------------|
| :terminal          | Abrir terminal integrado       |
| Ctrl + \ Ctrl + n| Voltar ao modo normal          |
| i                  | Entrar no modo de inserção     |

---

🧾 Cheatsheet Visual

`markdown
NEOVIM CHEATSHEET

📂 Arquivos
:w        → Salvar
:q        → Fechar
:wq       → Salvar e sair
:q!       → Sair sem salvar
:bn / :bp → Próximo / Anterior buffer
:bd       → Fechar buffer atual

🔍 Busca
/palavra   → Buscar
n / N      → Navegar resultados
:%s/a/b/g  → Substituir
:noh       → Limpar busca

🧠 LSP (coc.nvim)
gd        → Definição
gr        → Referências
gi        → Implementação
K         → Documentação
[d / ]d   → Navegar erros

🎨 Edição
gcc       → Comentar linha
yy / dd   → Copiar / Cortar
p         → Colar
u / Ctrl+r→ Desfazer / Refazer
>> / <<   → Indentar

🔄 Git
:G         → Status
:Gdiffsplit→ Diff
:Gblame    → Blame
:Gpush     → Push
:Gpull     → Pull

🖥 Terminal
:terminal  → Abrir terminal
Ctrl+\ Ctrl+n → Modo normal
`

---

🤝 Contribuindo

1. Faça um fork
2. Crie uma branch: git checkout -b minha-feature
3. Commit: git commit -m 'feat: minha nova feature'
4. Push: git push origin minha-feature
5. Abra um Pull Request

---

📄 Licença

Este projeto está sob a licença MIT.  
Use, modifique e compartilhe livremente.

---

