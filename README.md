# 📋 Gerenciador de Metas - CLI com Inquirer

Este projeto é um gerenciador de metas pessoais que roda diretamente no terminal (linha de comando), feito com Node.js e a biblioteca `@inquirer/prompts`. O usuário pode cadastrar novas metas e marcar como concluídas de forma interativa.

## 🚀 Funcionalidades

- [x] Cadastrar novas metas
- [x] Listar metas existentes
- [x] Marcar metas como concluídas usando interface interativa
- [x] Navegação via teclado (setas, espaço e enter)

## 🖥️ Demonstração

```bash
Menu >
❯ Cadastrar meta
  Listas metas
  Sair
```

Ao listar metas:

```bash
Use as setas para navegar e a barra de espaço para marcar ou desmarcar e Enter para finalizar esta etapa
◯ Tomar 3L de água por dia
◯ Fazer 30 minutos de caminhada
```

## 📦 Tecnologias usadas

- [Node.js](https://nodejs.org/)
- [@inquirer/prompts](https://www.npmjs.com/package/@inquirer/prompts)

## 📥 Instalação

```bash
git clone https://github.com/AndersonJunior95/Gerenciador-de-Metas.git
cd Gerenciador-de-Metas
npm install
node index.js
```

> **Atenção**: o arquivo principal deve ser chamado `index.js` (ou atualize conforme o nome real).

## 📁 Estrutura básica

```
index.js         # Arquivo principal do programa
package.json     # Dependências e scripts
```

## 🧠 Aprendizado

Este projeto foi criado para praticar:

- Manipulação de arrays e objetos em JavaScript
- Uso de `async/await` com prompts interativos
- Organização de lógica para aplicações CLI (Command Line Interface)

## 💡 Melhorias futuras

- [ ] Armazenar metas em arquivo JSON (para persistência)
- [x] Adicionar edição e remoção de metas
- [ ] Marcar metas com prazos e alertas

## 🧑‍💻 Autor

Anderson Gonçalves