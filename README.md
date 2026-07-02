<p align="center">
 <img src="https://capsule-render.vercel.app/api?type=waving&height=300&color=660000&text=Dashboard%20Vendas%20Porsche&descSize=40&fontAlign=51&animation=twinkling&fontAlignY=43&fontSize=30&reversal=true&section=header">
</p>

# 🏎️ Porsche Sales Intelligence Dashboard

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)

> Um dashboard executivo interativo em *Single File Component* (arquivo único) para análise de performance comercial da Porsche. 

Este projeto consolida KPIs, gráficos dinâmicos e tabelas operacionais em uma interface responsiva (Dark Mode). 
Ele foi projetado para ser uma alternativa web leve, rápida e sem dependências para o compartilhamento de painéis, 
complementando fluxos tradicionais de inteligência de negócios frequentemente feitos em ferramentas como Power BI ou planilhas complexas de Excel.

## 📸 Preview

<div align="center">
  <img src="" alt="Dash.png" width="800"/>
  <p><i>Substitua por uma captura de tela real do seu dashboard em funcionamento.</i></p>
</div>

## 📊 O Problema de Negócio

O objetivo desta visualização de dados é responder rapidamente a perguntas estratégicas para tomadas de decisão na ponta:
* Quais modelos lideram as vendas em cidades e estados específicos?
* Qual é a distribuição de vendas por ano de modelo (*Model Year*)?
* Quais os métodos de pagamento preferenciais por região?
* Quais são as recomendações imediatas (leitura executiva automatizada) com base no recorte filtrado?

## 🚀 Funcionalidades

* **Filtros Cruzados em Tempo Real:** Segmente toda a base de dados por *Modelo*, *Ano*, *Cidade* e *Método de Pagamento*.
* **KPIs Responsivos:** Recálculo automático de volume de vendas, receita total, ticket médio e modelos/anos dominantes.
* **Geração de Insights:** Motor simples via JavaScript que lê os dados filtrados e gera recomendações de negócio em texto.
* **Visualização de Dados Elegante (Chart.js):**
  * Gráfico de barras horizontais para mix de modelos.
  * Gráfico de rosca para distribuição temporal.
  * Gráfico de eixos duplos (Combo: Vendas x Receita) para performance por Estado.
* **Zero Configuração:** Basta abrir o arquivo `index.html` no navegador. Não requer Node, empacotadores ou servidores locais.

## 💻 Como Executar na Sua Máquina

Por ser construído inteiramente em Vanilla JS, HTML e CSS dentro de um único arquivo, a execução é imediata:

1. Clone este repositório:
   ```bash
   git clone [https://ds-rfta.github.io/dashboard_Porsche/](https://ds-rfta.github.io/dashboard_Porsche/)

!