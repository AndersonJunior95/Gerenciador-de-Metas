# 🚀 Gerenciador de Metas

Um aplicativo de linha de comando (CLI) simples para gerenciar metas e tarefas pessoais, desenvolvido em Node.js. Permite cadastrar, listar, marcar como concluídas, visualizar abertas, deletar e visualizar metas realizadas, tudo de forma interativa no terminal.

## ✨ Funcionalidades

- 📝 **Cadastrar meta:** Adicione novas metas/tarefas.
- 📋 **Listar metas:** Veja todas as metas e marque como concluídas.
- ✅ **Metas realizadas:** Visualize apenas as metas já concluídas.
- ⏳ **Metas abertas:** Visualize apenas as metas pendentes.
- 🗑️ **Deletar metas:** Remova metas selecionadas.
- 💾 **Persistência:** As metas são salvas em um arquivo `metas.json`.

## 💻 Demonstração

```bash
Menu >
❯ Cadastrar meta
  Listas metas
  Metas Realizadas
  Metas Abertas
  Deletar Metas
  Sair
```

## 🛠️ Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/AndersonJunior95/Gerenciador-de-Metas.git
   cd Gerenciador-de-Metas
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Execute o aplicativo:**
   ```bash
   node index.js
   ```

## 📂 Estrutura dos arquivos

- `index.js` — Código principal do aplicativo.
- `metas.json` — Arquivo onde as metas são salvas.
- `package.json` — Dependências do projeto.

## 🧰 Tecnologias utilizadas

- [Node.js](https://nodejs.org/)
- [Inquirer](https://www.npmjs.com/package/inquirer) (e @inquirer/prompts)

## 🚧 Possíveis melhorias

- 🔒 Adicionar autenticação de usuário.
- ✏️ Permitir editar metas.
- 📤 Exportar/importar metas.
- 🌐 Interface web ou mobile.

## 👤 Autor

Anderson  
[https://github.com/AndersonJunior95/Gerenciador-de-Metas](https://github.com/AndersonJunior95/Gerenciador-de-Metas)

---

Sinta-se à vontade para contribuir ou sugerir melhorias! 😃