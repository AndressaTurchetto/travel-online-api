
![Imagem de capa do curso "Angular: construa um Design System com Nx e Storybook", que faz parte da formação "Angular Design System". O logotipo do GitHub e o nome "/alura-cursos" estão no canto superior esquerdo, e o logotipo da Alura no canto superior direito. Na parte inferior direita, há uma indicação de que o curso faz parte da trilha de Front-end.](./thumb.png)

# Design System da Alfabit

Monorepo criado para implementação do Design System da empresa fictícia Alfabit, uma empresa de consultoria de software. Reconhecendo a importância do design consistente e intuitivo em todas as suas plataformas e produtos, a Alfabit decidiu investir em um Design System de ponta.

![Interface do Storybook exibindo exemplos de botões de uma biblioteca de componentes. À esquerda, há um menu com uma lista de stories organizados sob a pasta "button", incluindo 12 variantes de botões como "Primary Button", "Secondary Button", e suas versões desabilitadas. À direita, estão as pré-visualizações interativas dos componentes "Primary Button", "Primary Button Disabled" e "Secondary Button", cada um com a opção de visualizar o código fonte.](./project-thumb.png)

## 🔨 Funcionalidades do projeto

A biblioteca de botão criada no monorepo (mono-repositório) pode ser visualizada em um servidor do Storybook, onde foi feita uma documentação interativa do componente. Além disso, a publicação da biblioteca de botão foi automatizada com o Nx Release.

Acesse o [Figma do Design System](https://www.figma.com/community/file/1402315008064949507).

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
