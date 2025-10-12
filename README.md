# nvim

Perfeito, Luís! Então o seu nvim não é baseado em Lua (como a maioria das configs modernas), mas provavelmente em Vimscript (init.vim). Nesse caso, o README precisa refletir isso para não confundir quem for usar.  

Aqui vai uma versão ajustada para setups em Vimscript:

---

⚡ Neovim Config - Agência Martini Digital

Configuração personalizada do Neovim usando Vimscript (init.vim).  
Feita para oferecer praticidade, produtividade e um fluxo de trabalho simples e direto.

---

📦 Requisitos

Antes de instalar, verifique se você tem:

- Neovim >= 0.5
- Git
- Node.js (para plugins que dependem de JS/TS)
- Ripgrep (para busca avançada)

---

⚙️ Instalação

Clone este repositório dentro da pasta de configuração do Neovim:

`bash
git clone https://github.com/agenciamartinidigital-sy/nvim ~/.config/nvim
`

Abra o Neovim e rode:

`vim
:PlugInstall
`

> Obs: Este setup usa vim-plug como gerenciador de plugins.  
> Caso não tenha, instale seguindo as instruções: vim-plug.

---

🛠 Estrutura do Projeto

`
nvim/
├── init.vim        # Arquivo principal de configuração
├── plug.vim        # Lista de plugins
└── README.md
`

---

✨ Funcionalidades

- 🎨 Tema customizado e suporte a ícones
- 🔍 Busca rápida com fzf ou telescope
- 🧠 Autocompletion com coc.nvim
- 📜 Syntax highlight aprimorado
- 🔄 Integração com Git
- 🖥 Terminal integrado

---


📄 Licença

Este projeto está sob a licença MIT.  
Use, modifique e compartilhe livremente.

---


📝 Cheatsheet Visual

`
╔════════════════════════════════════════════════════════╗
║                    NEOVIM CHEATSHEET                   ║
╠════════════════════════════════════════════════════════╣
║ 📂 Arquivos & Buffers                                  ║
║ :w        → Salvar                                     ║
║ :q        → Fechar                                     ║
║ :wq       → Salvar e sair                              ║
║ :q!       → Sair sem salvar                            ║
║ :bn / :bp → Próximo / Anterior buffer                  ║
║ :bd       → Fechar buffer atual                        ║
╠════════════════════════════════════════════════════════╣
║ 🔍 Busca & Substituição                                ║
║ /palavra   → Buscar palavra                            ║
║ n / N      → Próxima / Anterior ocorrência             ║
║ :%s/a/b/g  → Substituir todas as ocorrências           ║
║ :noh       → Limpar highlights                         ║
╠════════════════════════════════════════════════════════╣
║ 🧠 LSP / Autocomplete (coc.nvim)                       ║
║ gd        → Ir para definição                          ║
║ gr        → Referências                                ║
║ gi        → Implementação                              ║
║ K         → Documentação                               ║
║ [d / ]d   → Navegar erros                              ║
║ <Tab>     → Completar sugestão                         ║
╠════════════════════════════════════════════════════════╣
║ 🎨 Edição & Produtividade                              ║
║ gcc       → Comentar linha                             ║
║ yy / dd   → Copiar / Recortar linha                    ║
║ p         → Colar                                      ║
║ u / Ctrl+r→ Desfazer / Refazer                         ║
║ >> / <<   → Indentar / Desindentar                     ║
╠════════════════════════════════════════════════════════╣
║ 🔄 Git (vim-fugitive)                                  ║
║ :G         → Status Git                                ║
║ :Gdiffsplit→ Diff lado a lado                          ║
║ :Gblame    → Blame da linha                            ║
║ :Gpush     → Push                                      ║
║ :Gpull     → Pull                                      ║
╠════════════════════════════════════════════════════════╣
║ 🖥 Terminal                                             ║
║ :terminal  → Abrir terminal integrado                  ║
║ Ctrl+\ Ctrl+n → Voltar ao modo normal                  ║
╚════════════════════════════════════════════════════════╝


