# 🌿 ONG Esperança Viva | Formulário de Cadastro de Voluntários

Este repositório contém o código de um formulário de cadastro desenvolvido com foco em acessibilidade e semântica, aplicando os conceitos aprendidos no curso superior (faculdade). O objetivo é simular a captação de voluntários para uma Organização Não Governamental (ONG) fictícia.

## 🎯 Objetivo do Projeto

O principal objetivo deste projeto é a prática e a demonstração da aplicação correta dos princípios do **HTML5 Semântico**, garantindo uma estrutura de código limpa, acessível e fácil de ser compreendida por máquinas (mecanismos de busca, leitores de tela) e por outros desenvolvedores.

---

## 💚 A ONG Esperança Viva

A **ONG Esperança Viva** é uma organização dedicada à promoção de ações sociais, ambientais e educacionais. A missão é conectar pessoas dispostas a dedicar seu tempo e talento para causar um impacto positivo na comunidade.

Este formulário é a porta de entrada para novos voluntários, sendo crucial que sua interface seja intuitiva e seu código, robusto e padronizado.

---

## 🛠️ Tecnologias e Conceitos Aplicados

O projeto foi desenvolvido utilizando os padrões mais recentes do desenvolvimento web:

| Conceito | Aplicação no Código |
| :--- | :--- |
| **HTML5 Semântico** | Utilização correta de elementos estruturais como `<header>`, `<nav>`, `<main>`, `<section>`, `<form>` e `<fieldset>` para definir o papel de cada parte do conteúdo. |
| **Validação W3C** | O código foi validado no W3C Validator para garantir a conformidade com as especificações, eliminando erros de fechamento e estrutura. |
| **Acessibilidade (ARIA)** | Uso de atributos `for` nas tags `<label>` e `id` nos `<input>` para conectar campos de formulário, melhorando a experiência para leitores de tela. |
| **Validação de Formulário** | Uso de atributos HTML5 como `required`, `type="email"`, `maxlength` e `pattern` (Regex) para validação inicial de dados (CPF, Telefone, CEP) diretamente no cliente. |
| **Meta Tags** | Configuração de tags essenciais (`<meta charset>`, `<meta name="viewport">`) para responsividade e compatibilidade. |

### Destaques Semânticos e de Validação

* **Estrutura de Conteúdo:** O bloco principal do formulário está contido em `<main>` e agrupado em uma `<section>`, indicando claramente seu papel no documento.
* **Agrupamento de Campos:** O `<fieldset>` e o `<legend>` foram usados corretamente para agrupar visual e semanticamente as "Informações Pessoais", tornando o formulário mais organizado para o usuário e para leitores de tela.
* **Tag de Vazio:** A tag `<input type="submit">` foi corrigida para o padrão HTML5, não utilizando o fechamento automático `/>` (self-closing), conforme as diretrizes de elementos de vazio.

---

## 🔗 Link do Projeto

`https://VagnerDevBR.github.io/cadastro-voluntarios-ong/`

## 📂 Como Acessar o Código

O código-fonte completo pode ser encontrado na branch principal deste repositório.

---

