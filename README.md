# MyStudyTasks 📚

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visitar%20App-brightgreen)](https://almeida-cma.github.io/tarefas/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Um organizador de tarefas de estudo completo, interativo e 100% personalizável, desenvolvido com HTML, CSS e JavaScript puros. Este projeto foi criado como um *case de estudo* prático para a aula **"Da Ideia ao App: Crie Sua Inovação"**, demonstrando a jornada completa desde a concepção de uma ideia até um aplicativo web funcional, robusto e focado na experiência do usuário.

> ### Acesse a versão ao vivo: [https://almeida-cma.github.io/tarefas/](https://almeida-cma.github.io/tarefas/)


---

## ✨ Funcionalidades Principais

O **MyStudyTasks** não é apenas uma lista de tarefas. É uma ferramenta completa de produtividade com recursos pensados para o dia a dia do estudante:

*   **Gestão Completa de Tarefas (CRUD):** Crie, edite (com detalhes como descrição, prioridade, categoria e data), marque como concluída e exclua tarefas com feedback sonoro para cada ação.
*   **Organização Avançada:**
    *   **Prioridades:** Classifique tarefas como Alta, Média ou Baixa.
    *   **Categorias:** Organize suas tarefas por matéria ou projeto (ex: "Matemática", "História").
    *   **Datas de Vencimento:** Defina prazos e receba alertas visuais.
*   **Filtros Inteligentes e Combinados:** Filtre sua lista por **Status** (Pendentes, Concluídas), **Prioridade** e **Categoria** de forma simultânea para focar no que realmente importa.
*   **Personalização Total:**
    *   **Editor de Tema:** Mude as cores primária, secundária, de destaque, de fundo e dos cards em tempo real.
    *   **Ícones e Título:** Personalize o ícone e o título do aplicativo.
    *   **Sons Configuráveis:** Escolha entre diferentes sons para ações de conclusão e notificação.
*   **Feedback Imediato:**
    *   **Alertas Visuais:** Tarefas com vencimento para o dia (🟡) ou atrasadas (🔴) são destacadas automaticamente.
    *   **Notificações Sonoras:** Cada ação importante é confirmada com um som para uma melhor experiência do usuário.
*   **Acessibilidade:**
    *   **Ajuste de Fonte:** Aumente ou diminua o tamanho do texto.
    *   **Modo Escuro:** Tema otimizado para ambientes com pouca luz.
    *   **Leitura em Voz Alta:** Ouça um resumo das suas tarefas pendentes, com a opção de interromper a leitura a qualquer momento.
*   **Portabilidade de Dados:**
    *   **Backup (JSON):** Exporte todas as suas tarefas para um arquivo JSON para backup ou para movê-las entre dispositivos.
    *   **Importação (JSON):** Importe um arquivo de backup, com a opção de substituir ou mesclar com as tarefas existentes.
    *   **Exportação Inteligente (TXT):** Exporte um arquivo `.txt` contendo apenas as tarefas visíveis na tela, de acordo com os filtros aplicados.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído do zero, utilizando apenas as tecnologias fundamentais da web, sem frameworks ou bibliotecas externas.

*   **HTML5:** Estrutura semântica e acessível.
*   **CSS3:** Estilização moderna com:
    *   Variáveis CSS (Custom Properties) para fácil customização e temas.
    *   Flexbox e Grid Layout para responsividade.
    *   Animações sutis para uma melhor experiência de usuário.
*   **JavaScript (ES6+):** Lógica do aplicativo, manipulação do DOM e interatividade.
    *   **localStorage:** Para persistência de dados, salvando as tarefas e personalizações diretamente no navegador do usuário.
    *   **Web Audio API:** Para geração dinâmica dos sons de feedback.

---

## 📂 Estrutura do Projeto

O repositório é intencionalmente simples para focar no aprendizado do código-fonte.

```bash
/
├── index.html     # O arquivo principal do aplicativo. Contém todo o HTML, CSS e JavaScript.
└── Manual.pdf     # O manual completo do usuário em formato PDF.
