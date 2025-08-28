# Infográfico: O Dilema da Justiça Preditiva (Caso COMPAS)

![Licença](https://img.shields.io/badge/license-MIT-blue.svg)
[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen)](https://SEU-NOME-DE-USUARIO.github.io/infografico-justica-ia/infografico.html)

Infográfico interativo que explora o viés algorítmico e as implicações éticas do sistema de IA **COMPAS**, utilizado no sistema de justiça criminal dos EUA. Este projeto foi desenvolvido como uma ferramenta visual para educar e provocar a reflexão sobre a responsabilidade no uso de inteligência artificial em decisões críticas.

## 🚀 Demo Online

**Acesse a versão interativa do infográfico aqui:**

[https://esthevamnascimento.github.io/infografico-justica-ia/infografico.html](https://esthevamnascimento.github.io/infografico-justica-ia/infografico.html)



## ✨ Funcionalidades Principais

* **Visualização de Dados:** Gráficos interativos (barras e rosca) criados com **Chart.js** para exibir as disparidades nas taxas de erro do algoritmo COMPAS.
* **Análise Ética com IA:** Uma seção interativa que utiliza a **API do Google Gemini** para gerar uma análise ética sobre um perfil hipotético, demonstrando os riscos da automação de decisões judiciais.
* **Conteúdo Didático:** Explicações claras sobre conceitos complexos, como "Falsos Positivos" e o "Teorema da Impossibilidade da Justiça".
* **Design Responsivo:** Interface limpa e adaptável a diferentes tamanhos de tela, construída com **Tailwind CSS**.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação do conteúdo.
* **Tailwind CSS:** Estilização e design responsivo.
* **JavaScript (ES6+):** Interatividade, manipulação do DOM e lógica da aplicação.
* **Chart.js:** Renderização dos gráficos de dados.
* **Google Gemini API:** Para a funcionalidade de análise de caso interativa.

## ⚙️ Como Executar o Projeto Localmente

Para rodar este projeto no seu próprio computador, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU-NOME-DE-USUARIO/infografico-justica-ia.git](https://github.com/SEU-NOME-DE-USUARIO/infografico-justica-ia.git)
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd infografico-justica-ia
    ```

3.  **Adicione sua Chave de API:**
    * Abra o arquivo `infografico.html` em um editor de código.
    * Procure pela linha que contém `const apiKey = "SUA_CHAVE_API_AQUI";`.
    * Substitua `"SUA_CHAVE_API_AQUI"` pela sua chave de API do Google Gemini, que pode ser obtida no [Google AI Studio](https://aistudio.google.com/).

4.  **Abra o arquivo no navegador:**
    * Clique duas vezes no arquivo `infografico.html` ou o arraste para a janela do seu navegador preferido.

## ⚖️ O Desafio Ético Abordado

O sistema COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) foi alvo de uma investigação da ProPublica em 2016, que revelou um viés racial significativo. O algoritmo, que deveria ser neutro, classificava réus negros como tendo o dobro de chances de reincidir em comparação com réus brancos, mesmo quando isso não se confirmava. Este projeto busca materializar esses dados e discutir por que a busca por uma "justiça algorítmica" é um desafio complexo e repleto de dilemas éticos.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
