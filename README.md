# 📚 Biblioteca Digital UniFECAF — Projeto Design Web

> **Projeto Acadêmico** desenvolvido para a disciplina de **Design Web** do Centro Universitário **UniFECAF**.
>
> **Estudante / Desenvolvedor:** Wellington Diego Santos da Silva
> **Status do Projeto:** 🟢 Concluído e Publicado

---

## 🌐 Links Rápidos
* 🚀 **Acesse o Site Online (GitHub Pages):** [https://wellingtondsilva.github.io/biblioteca-unifecaf/index.html]
* 📂 **Repositório do Código-Fonte:** [https://github.com/Wellingtondsilva/biblioteca-unifecaf.git]
* ▶️ **Vídeo do YouTube:** [https://youtu.be/VKkHSyMSqzA]

---

## 📌 Sobre o Projeto

A UniFECAF identificou a necessidade de desenvolver a primeira interface web de sua **Biblioteca Digital** para facilitar o acesso de alunos, professores e colaboradores a livros digitais, materiais acadêmicos e informações sobre suas unidades físicas e ambiente virtual de aprendizagem (AVA).

O objetivo principal deste projeto foi interpretar o protótipo de baixa fidelidade (*wireframe*) disponibilizado na disciplina e transformá-lo em uma plataforma web **moderna, intuitiva, totalmente responsiva e acessível**, utilizando exclusivamente **HTML5** e **CSS3** puros (sem dependência de frameworks externos como Bootstrap).

### 🎯 Principais Funcionalidades Implementadas
* **Interface Semântica e Acessível:** Estruturada com tags semânticas do HTML5 e boas práticas de contraste cromático.
* **Acervo Digital em Destaque:** Exibição de 8 obras com capas reais em alta definição.
* **Navegação Dinâmica para Detalhes (`livro.html`):** Ao clicar em qualquer livro do acervo, o usuário é direcionado para uma página dedicada com sinopse completa, editora, autor e opções de leitura.
* **Design Totalmente Responsivo:** Adaptação fluida do layout para computadores de mesa, tablets e smartphones.
* **Rodapé Institucional com Redes Sociais:** Inclusão de acessos diretos para Instagram, TikTok, YouTube, Facebook e LinkedIn da UniFECAF.

---

## 🎨 Identidade Visual e Design

A interface foi desenvolvida seguindo estritamente o guia de marca e a identidade institucional da UniFECAF:

* **Paleta de Cores:**
  * **Azul Escuro Institucional (`#002B49`):** Cor primária; transmite solidez, autoridade e confiança.
  * **Azul Cyan (`#00A3E0`):** Cor secundária; aplicada em ícones, badges e efeitos de *hover* para indicar tecnologia.
  * **Laranja de Ação (`#FF6B00`):** Cor de acento; utilizada nos botões de chamada para ação (CTA) para orientar a navegação do usuário.
  * **Fundo Neutro (`#F4F7FA` e `#FFFFFF`):** Espaço negativo para conforto visual durante a leitura.
* **Tipografia:**
  * **Títulos (`Montserrat`):** Tipografia sem serifa de forte impacto visual.
  * **Textos de Corpo (`Open Sans`):** Tipografia otimizada para leitura confortável em telas de diferentes resoluções.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica de todo o conteúdo e componentes.
* **CSS3:** Estilização, layout flexível (CSS Grid & Flexbox), animações e regras de responsividade (`@media queries`).
* **JavaScript Vanilla:** Utilizado pontualmente na página `livro.html` para extrair os dados da URL e carregar a sinopse dinamicamente sem recarregar o servidor.
* **Font Awesome v6:** Biblioteca de ícones vetoriais.
* **Google Fonts:** Importação das famílias tipográficas Montserrat e Open Sans.

---

## 📂 Estrutura de Arquivos do Repositório

O projeto foi organizado de forma limpa, padrão e legível conforme exigido nas diretrizes do trabalho.

```text
biblioteca-unifecaf/
│
├── index.html                # Página principal (Home, Sobre, Acervo e Unidades)
├── livro.html                # Página secundária de detalhes e sinopse do livro
├── README.md                 # Documentação completa do repositório
│
├── css/
│   └── style.css             # Folha de estilos unificada e comentada
│
└── assets/
    └── imagens/              # Capas em alta resolução dos livros cadastrados
        ├── ADMINISTRAÇÃO MODERNA.jpg
        ├── CRIANDO SITES COM HTML.jpg
        ├── CURSO DE DIREITO CONSTITUCIONAL.jpg
        ├── DESIGN DIGITAL.jpg
        ├── FUNDAMENTOS DE HTML5 E CSS3.jpg
        ├── INTRODUÇÃO A PROGRAMAÇÃO COM PYTHON.jpg
        ├── MARKETING DIGITAL.jpg
        └── PSICOLOGIA COGNITIVA.jpg
===================================================================================================
📜 Licença e Direitos Autorais
Este projeto foi desenvolvido estritamente para fins acadêmicos e pedagógicos no Centro Universitário UniFECAF. Todos os direitos das marcas e logotipos pertencem à UniFECAF.