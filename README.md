# Planej.ai

O Planej.ai é uma aplicação web de planejamento financeiro pessoal desenvolvida com React e TypeScript.

A aplicação permite que a pessoa usuária informe sua renda, gastos, dívidas e uma meta financeira. Ao finalizar a simulação, os dados são armazenados no navegador e utilizados para gerar um diagnóstico financeiro personalizado com IA Generativa.

## Tecnologias

- React
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Gemini API
- LocalStorage
- Lucide React

## Funcionalidades

- Formulário financeiro em múltiplas etapas
- Tema claro e escuro
- Persistência das simulações no LocalStorage
- Página de resultados
- Geração de insights com IA
- Tratamento de carregamento e erros
- Histórico de simulações

## Minha melhoria

Implementei uma página de histórico de simulações.

A funcionalidade permite visualizar todas as simulações armazenadas no navegador e acessar novamente o resultado de cada uma através do seu identificador único.

Para isso, foi adicionada a função `getAllFormData` ao hook `useSimulationStorage` e criada uma nova página `HistoryPage`.

Também foi adicionada a rota `/historico` e a navegação pelo Header.

## Como testar

1. Execute o projeto.
2. Crie uma nova simulação.
3. Finalize o formulário.
4. Acesse o menu Histórico.
5. Verifique a simulação criada.
6. Clique em "Ver simulação".
7. Crie uma segunda simulação e confirme que as duas aparecem no histórico.

## O que aprendi

Durante o desenvolvimento, pratiquei:

- Componentização com React;
- gerenciamento de estado com `useState`;
- navegação com React Router;
- tipagem com TypeScript;
- organização por responsabilidade;
- manipulação de objetos e arrays;
- persistência com LocalStorage;
- criação e utilização de hooks;
- integração de Front-End com IA Generativa;
- criação de funcionalidades a partir de uma aplicação existente.

Também aprendi a analisar a estrutura de um projeto antes de modificar o código e a entender como diferentes partes da aplicação se comunicam.
