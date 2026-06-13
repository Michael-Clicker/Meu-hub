# Meu-Hub | Terminal Portfolio

Uma aplicação web responsiva desenvolvida como centralizadora de links profissionais e portfólio pessoal. O projeto adota uma estética imersiva baseada em interfaces de linha de comando (CLI) e ambientes de desenvolvimento modernos (IDEs), organizando os principais projetos em um único ponto de acesso. 

## 🔄 Histórico de Versões (Changelog)

### [V2.0] - Versão Atual (Redesign Técnico)
* **Mudança de Paradigma Visual:** Transição completa de um layout padrão e genérico (estilo Linktree) para uma interface totalmente customizada baseada na cultura de desenvolvimento (Terminal Hacker).
* **Migração para CSS Grid:** Substituição da estrutura de blocos centralizados simples por uma arquitetura de tela dividida (*split-screen*) estável e rolagens independentes.

### [V1.0] - Versão Legado (Estrutura Inicial)
* Primeira versão simplificada do agregador de links, utilizando um tema claro convencional e cartões estruturados básicos para direcionamento rápido às redes sociais.

## 📷 Demonstração Visual (Antes vs. Depois)

Para ilustrar a evolução da interface, o projeto passou por uma reformulação completa de layout e proposta visual:

| V1.0 - Versão Legado (Padrão Linktree) | V2.0 - Versão Atual (Padrão Terminal) |
| :---: | :---: |
| <img alt="v1-legado" src="https://github.com/user-attachments/assets/a1ad9ec2-5f88-4e6e-ae86-c53743a25d18" width="450px"/> | <img width="450" alt="v2-terminal" src="https://github.com/user-attachments/assets/dc670a00-c9da-446a-8d52-f4a145c8d932" />


## 🚀 Funcionalidades

* **Arquitetura Split-Screen Responsiva:** Layout dinâmico utilizando CSS Grid que divide a tela em uma barra lateral fixa de perfil (35%) e uma área rolável de conteúdo (65%) em desktops, adaptando-se para um fluxo vertical fluido em dispositivos móveis.
* **Centralização de Repositórios:** Navegação estruturada contendo links diretos para projetos reais (como ferramentas de análise de dados, automações backend e utilitários em JavaScript).
* **Indicadores Visuais de Status:** Bloco dedicado a exibir em tempo real o foco atual de estudos e tecnologias ativas de desenvolvimento.
* **Navegação Semântica e Acessível:** Uso rigoroso de tags HTML5 estruturais (`<main>`, `<section>`, `<nav>`, `<footer>`) e atributos de acessibilidade como `aria-label` para garantir melhor leitura por leitores de tela e indexadores SEO.

## 🎨 Identidade Visual e Interface

O design foi inteiramente planejado para emular a experiência de um terminal de desenvolvimento técnico clássico, priorizando legibilidade, minimalismo e alto contraste.
* **Recorte Geométrico Avançado:** Customização da foto de perfil integrada nativamente em formato hexagonal utilizando manipulação geométrica via CSS (`clip-path`), dispensando o uso de editores de imagem externos.
* **Paleta de Cores Monocromática com Accent:** Base escura profunda inspirada no ecossistema GitHub Dark (`#0d1117` / `#161b22`) com realce sintático em tons verdes característicos de terminais (`#3fb950`).
* **Microinterações de Feedback:** Transições dinâmicas ao passar o mouse (`hover`) que deslocam os links horizontalmente (`translateX(5px)`), alteram a cor de exibição e revelam ponteiros indicadores de linha (`->`).

## 💻 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica limpa, sem dependências de frameworks, otimizando o tempo de carregamento da página.
* **CSS3 Moderno:** Arquitetura construída com propriedades personalizadas (`:root`), flexbox para alinhamentos internos, CSS Grid para o esqueleto principal da página e Media Queries para adaptação mobile total.

## 🧠 Aprendizado e Evolução Técnica

A concepção deste hub serviu para consolidar competências cruciais de design de interface limpo e arquitetura CSS estável:
* **Domínio de Escopo e Variáveis Globais:** Uso eficiente de variáveis CSS para centralização de tokens de design (cores, fontes e espaçamentos), permitindo manutenção rápida ou futuras trocas de temas.
* **Resolução de Problemas de Layout Sem Frameworks:** Criação de uma interface dividida e com rolagens independentes puramente com CSS nativo, aprofundando o conhecimento em modelos de caixa (`box-sizing`) e fluxos de renderização de tela.

## 🔮 Próximos Passos (Roadmap de Implementação)

* **Integração de JavaScript Dinâmico para Descrições:** Desenvolvimento de uma camada interativa utilizando Vanilla JS para otimizar o espaço visual da tela. Os comentários explicativos (`// descrição`) serão ocultados por padrão e exibidos dinamicamente apenas quando o usuário passar o mouse sobre o respectivo link. A lógica será estruturada manipulando o DOM por meio de ouvintes de eventos (`addEventListener` com os gatilhos `mouseover` e `mouseout` ou `mouseenter` e `mouseleave`), alterando as classes ou opacidades dos elementos em tempo de execução.

## 🔧 Como Executar o Projeto

O projeto pode ser acessado em: https://michael-clicker.github.io/Meu-hub/
