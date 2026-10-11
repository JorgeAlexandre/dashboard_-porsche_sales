# 🏁 Dashboard de Vendas Porsche 

Este repositório contém uma **dashboard interativa e refinada** para análise de dados de vendas de modelos Porsche, desenvolvida com foco em inteligência de negócios (BI), UX/UI premium e autonomia de análise sem as limitações de planilhas tradicionais.

O projeto faz parte do desafio prático do **Curso Santander - Excel com IA e Claude**, com o objetivo de transformar dados brutos de uma planilha sanitizada em uma aplicação web funcional, estática e de arquivo único (`index.html`), publicada via **GitHub Pages**.

---

## 🎯 O Desafio & Escopo do Projeto

O objetivo principal é responder a perguntas estratégicas de negócio por meio de indicadores de topo e gráficos dinâmicos, utilizando filtros interativos que segmentam a base de dados.

### Requisitos Funcionais Implementados:
*   **Filtros Dinâmicos:**
    *   Modelo da Porsche
    *   Ano do Modelo (*Model Year*)
    *   Cidade (*City*)
    *   Método de Pagamento (*Pay Method*)
*   **Indicadores de Topo (KPIs):**
    *   Total de Vendas Realizadas (Volume)
    *   Receita Total Gerada
*   **Perguntas de Negócio Respondidas:**
    1. **Modelos por Cidade/Estado:** Quais os principais modelos de carros vendidos por localidade? (Apresentado via painel/gráfico comparativo).
    2. **Modelo Mais Vendido no Período:** Qual o modelo de carro que mais saiu em um recorte de tempo específico?
    3. **Insight de Carros Populares por Cidade:** Quais são os carros mais populares de vendas com base no comportamento e dados de cada mercado local?

---

## 🎨 Identidade Visual (UI/UX)

O design da interface foi projetado com base no **site oficial da Porsche Brasil**, buscando um ar extremamente **elegante, minimalista e refinado**:
*   **Tipografia & Cores:** Uso de fontes limpas, contrastes sóbrios e elementos inspirados no portal institucional da marca.
*   **Aparência:** Tons escuros/claros balanceados, linhas finas e precisas que remetem à performance esportiva clássica da Porsche.

---

## 🛠️ Como o Projeto Foi Construído (Metodologia)

O desenvolvimento seguiu os quatro passos estruturais recomendados pelo modelo de aprendizado:

1.  **Sanitização da Base:** Preparação da planilha original, mantendo apenas colunas limpas, convertendo preços e anos estritamente para o formato numérico e colando como valores (eliminando fórmulas quebradas).
2.  **Engenharia de Prompt (Canvas):** Utilização de diretrizes estruturadas e referências visuais da Porsche para a geração do código do painel interativo em um arquivo único.
3.  **Refinamento Continuo:** Ajustes finos em linguagem natural para calibração dos gráficos, filtros lógicos e correções diretamente via console de desenvolvedor.
4.  **Publicação:** Salvamento do arquivo como `index.html` e upload para este repositório no GitHub.

---

## 🚀 Como Visualizar a Dashboard Online

A aplicação está hospedada e configurada diretamente pelo **GitHub Pages**. Para acessá-la, basta ativar o recurso ou clicar no link de publicação do repositório:

1. Vá em **Settings** (Configurações) no menu superior deste repositório.
2. No menu lateral esquerdo, clique em **Pages**.
3. Na seção *Build and deployment*, certifique-se de que a origem (*Source*) está definida como **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)`. Clique em **Save**.
5. Em alguns instantes, o GitHub gerará um link público (ex: `https://seu-usuario.github.io/dashboard_-porsche_sales/`) onde a dashboard estará 100% interativa e online!

---
*Este projeto foi desenvolvido como critério prático de aplicação de IA aplicada à análise de dados.*
