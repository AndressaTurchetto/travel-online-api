# Lib Teste

Monorepo criado para implementação do Design System da empresa fictícia Lib Teste, uma empresa de consultoria de software. Reconhecendo a importância do design consistente e intuitivo em todas as suas plataformas e produtos, a Lib Teste decidiu investir em um Design System de ponta.

![Interface do Storybook exibindo exemplos de botões de uma biblioteca de componentes. À esquerda, há um menu com uma lista de stories organizados sob a pasta "button", incluindo 12 variantes de botões como "Primary Button", "Secondary Button", e suas versões desabilitadas. À direita, estão as pré-visualizações interativas dos componentes "Primary Button", "Primary Button Disabled" e "Secondary Button", cada um com a opção de visualizar o código fonte.](./project-thumb.png)

## 🔨 Funcionalidades do projeto

A biblioteca de botão criada no monorepo (mono-repositório) pode ser visualizada em um servidor do Storybook, onde foi feita uma documentação interativa do componente. Além disso, a publicação da biblioteca de botão foi automatizada com o Nx Release.

## ✔️ Técnicas e tecnologias utilizadas

As técnicas e tecnologias utilizadas pra isso são:

- **Design System e Atomic Design**: criados pela equipe de design para
organizar o Design System da empresa
- **Angular**: framework utilizado para implementação dos componentes
- **Nx e monorepo**: utilizados para criar e gerenciar aplicações e bibliotecas de forma produtiva
- **Storybook**: ferramenta para criação de documentação interativa
- **Nx Release**: recurso do Nx que facilita a automatização da publicação de bibliotecas

## 🛠️ Abrir e rodar o projeto

Após baixar ou clonar o projeto, execute o seguinte comando para subir o servidor do Storybook:

```bash
npx nx run storybook-host:storybook
# ou:
npx nx storybook storybook-host
```
