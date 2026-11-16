# Portfólio Pessoal - Desenvolvimento de Sistemas

**Aluno:** Guilherme

## Descrição do Portfólio
Este projeto consiste no desenvolvimento e evolução do meu portfólio pessoal profissional, criado como atividade da Agenda 15 do curso de Desenvolvimento de Sistemas. O objetivo da página é apresentar meu perfil, minhas competências técnicas, projetos desenvolvidos e um canal direto para contato.

## Tecnologias Utilizadas
* **HTML5:** Estruturação semântica do conteúdo.
* **CSS3:** Estilização personalizada e transições visuais.
* **Bootstrap 5:** Sistema de grid responsivo, barra de navegação, cards e formulário.
* **Git & GitHub Pages:** Versionamento de código e hospedagem gratuita do site.

## Link do Site Publicado
Acesse o portfólio online através do GitHub Pages: [Clique aqui para acessar](https://github.io)

## Explicação do Funcionamento do Projeto
O site funciona como uma *Single Page Application* (página única) responsiva. O usuário utiliza o menu superior fixo (`navbar`) para navegar suavemente entre as seções de Perfil, Habilidades, Projetos e Contato, adaptando-se automaticamente a telas de computadores, tablets e celulares.

## Recurso Novo Adicionado
Foram adicionados dois recursos extras além do modelo base de aula:
1. **Nova Seção de Habilidades:** Implementação de barras de progresso (`progress-bar`) exibindo o nível de domínio nas tecnologias estudadas.
2. **Animações de Hover:** Efeito visual de elevação e sombra nos cartões da seção de Projetos ao passar o cursor do mouse.

## Como o Recurso foi Implementado
* **Seção de Habilidades:** Foi criada uma nova `<section id="habilidades">` utilizando os componentes nativos `progress` e `progress-bar` do Bootstrap 5, vinculando o `id` ao menu de navegação superior.
* **Animações de Hover:** Foi criada a classe CSS `.card-projeto` aplicando a propriedade `transition: transform 0.3s ease, box-shadow 0.3s ease;` combinada com a pseudoclasse `:hover` utilizando `transform: translateY(-8px);`.
