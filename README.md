# Teste-De-Software-na-pra-tica

# 🛡️ Guia de Engenharia de Testes de Software

Este repositório é um guia abrangente que explora as diversas **fases, níveis e técnicas de teste de software**. O objetivo é servir como uma base de conhecimento para desenvolvedores e QAs que buscam garantir a entrega de produtos com alta qualidade e confiabilidade.

---

## 📑 Sumário

* [O que é Teste de Software?](https://www.google.com/search?q=%23o-que-%C3%A9-teste-de-software)
* [Níveis de Teste (Pirâmide de Testes)](https://www.google.com/search?q=%23n%C3%ADveis-de-teste)
* [Tipos de Teste](https://www.google.com/search?q=%23tipos-de-teste)
* [Técnicas de Teste](https://www.google.com/search?q=%23t%C3%A9cnicas-de-teste)
* [Ferramentas Recomendadas](https://www.google.com/search?q=%23ferramentas-recomendadas)

---

## 🧐 O que é Teste de Software?

Testar software não é apenas "encontrar bugs". É um processo de execução de um programa com a intenção de verificar se ele satisfaz os requisitos de negócio e identificar discrepâncias entre o comportamento esperado e o real.

---

## 🏗️ Níveis de Teste

A estratégia de testes geralmente segue a estrutura de uma pirâmide, onde a base (maior volume) foca na rapidez e baixo custo, e o topo foca na experiência completa do usuário.

1. **Testes de Unidade:** Validam a menor parte testável de um sistema (funções, métodos ou classes) de forma isolada.
2. **Testes de Integração:** Verificam se diferentes módulos ou serviços funcionam bem quando combinados.
3. **Testes de Sistema (E2E):** Testam a aplicação completa, do início ao fim, simulando o comportamento do usuário real.
4. **Testes de Aceitação (UAT):** Validação final realizada pelo cliente ou usuário final para garantir que o produto atende às necessidades.

---

## 🔍 Tipos de Teste

Podemos classificar os testes em dois grandes grupos:

| Tipo | Descrição | Exemplos |
| --- | --- | --- |
| **Funcionais** | Focam no *que* o sistema faz. | Teste de login, cadastro, cálculos. |
| **Não-Funcionais** | Focam no *como* o sistema opera. | Performance, Segurança, Usabilidade, Carga. |

---

## 🛠️ Técnicas de Teste

### 1. Teste de Caixa Preta (Black-Box)

Foca nas entradas e saídas sem considerar a estrutura interna do código.

* **Particionamento de Equivalência:** Divide os dados de entrada em classes que devem ser processadas da mesma forma.
* **Análise de Valor Limite:** Testa os extremos dos intervalos permitidos.

### 2. Teste de Caixa Branca (White-Box)

Analisa a estrutura interna, o design e o código do software.

* **Cobertura de Código:** Mede quanto do código é executado pelos testes.
* **Teste de Caminho:** Garante que todos os caminhos lógicos possíveis foram percorridos.

---

## 🚀 Ferramentas Recomendadas

* **Unitários:** Jest, JUnit, PyTest.
* **E2E / Automação:** Cypress, Selenium, Playwright.
* **API:** Postman, RestAssured.
* **Performance:** JMeter, K6.

---

## 🤝 Como contribuir

Encontrou um erro ou quer adicionar uma nova técnica?

1. Faça um **Fork** do projeto.
2. Crie uma **Branch** (`git checkout -b feature/nova-tecnica`).
3. Dê um **Commit** (`git commit -m 'Add: Técnica X'`).
4. Envie um **Pull Request**.

---

> "Testar é a busca disciplinada pela imperfeição."

Praticando
🐍 Testes com Python
Python é amplamente utilizado por sua sintaxe limpa e frameworks poderosos como Pytest (o padrão da indústria) e unittest.

1. Teste de Unidade (Pytest)
Focado em testar uma lógica isolada.

2. Teste de API (Requests + Pytest)
Validando se um endpoint retorna os dados corretos.

🚀 Testes com JavaScript/TypeScript
No ecossistema JS, o foco costuma ser em Jest para unidades/integração e Cypress ou Playwright para testes de interface (E2E).

1. Teste de Unidade (Jest)
Ideal para testar funções de utilidade ou componentes.

2. Teste End-to-End (Cypress)
Simula um usuário real interagindo com o navegador.

📊 Comparativo de Ecossistemas
Qual o próximo passo?
Como você mencionou as duas linguagens, eu poderia:

Criar um exemplo de CI/CD (GitHub Actions) para rodar esses testes automaticamente em cada "push".

Explicar como fazer Mocking (simular bancos de dados ou APIs) em uma dessas linguagens.

Mostrar como configurar o Playwright, que hoje é a ferramenta que une o melhor dos dois mundos (roda em Python e JS).
