🎮 Jogo da Velha (Tic-Tac-Toe) — React + TypeScript

Este projeto foi desenvolvido como meu primeiro contato com React e TypeScript.

O objetivo foi entender na prática os conceitos fundamentais da biblioteca, utilizando como base a documentação oficial do React:

🔗 https://react.dev/learn/tutorial-tic-tac-toe

🚀 Tecnologias Utilizadas

React

TypeScript

Vite

CSS

📚 O que aprendi neste projeto

Durante o desenvolvimento, pratiquei e compreendi:

✔ Componentes Funcionais

✔ Props

✔ useState

✔ Elevação de estado (Lifting State Up)

✔ Imutabilidade de arrays

✔ Renderização condicional

✔ Manipulação de eventos

✔ Tipagem com TypeScript em componentes React

✔ Organização básica de estrutura de projeto

🧠 Conceitos importantes aplicados
🔹 Estado e Histórico de Jogadas

O projeto implementa:

Armazenamento do histórico de jogadas

Navegação entre movimentos anteriores

Cálculo automático do vencedor

Isso ajudou a entender como o React lida com re-renderização baseada em estado.

🔹 Tipagem com TypeScript

Foram criadas interfaces para tipagem das props:

interface SquareProps {
  value: string | null;
  onSquareClick: () => void;
}

Esse foi meu primeiro contato prático com TypeScript aplicado ao React.

📂 Estrutura do Projeto
src/
 ├── App.tsx
 ├── main.tsx
 ├── index.css
 └── components (estrutura modular futura)
🎯 Objetivo do Projeto

Este projeto teve como foco:

Entender como o React funciona internamente

Compreender fluxo de dados entre componentes

Praticar organização de estado

Dar o primeiro passo na migração para desenvolvimento front-end

🛠 Como rodar o projeto
npm install
npm run dev
📈 Próximos Passos

Como evolução, pretendo:

Melhorar a interface

Separar componentes em arquivos individuais

Aplicar boas práticas de organização

Criar novos projetos com CRUD e integração com API

📌 Observação

Este projeto foi desenvolvido como parte do meu processo de transição da área de Infraestrutura para Desenvolvimento, marcando meu primeiro contato prático com React e TypeScript.