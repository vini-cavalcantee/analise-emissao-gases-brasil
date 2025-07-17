# Análise de Emissões de Gases por Estado Brasileiro

## Descrição do Projeto
Este projeto tem como objetivo analisar dados sobre as emissões de gases por estado no Brasil, relacionando essas emissões com a população local. Por meio da manipulação e visualização dos dados, buscando responder perguntas como:

- Os estados mais populosos são também os maiores emissores?
- Quais estados têm maior emissão per capita?
- Existe um padrão de comportamento entre as regiões?

---

## Tecnologias e Bibliotecas Utilizadas
- **Python 3**  
- **Pandas** — manipulação de dados  
- **Matplotlib** e **Plotly** — visualização gráfica  
- **Expressões Regulares (Regex)** — limpeza e tratamento dos dados  

---

## O que foi feito?
- **Leitura e limpeza dos dados:** remoção de caracteres desnecessários nas colunas populacionais.  
- **Agrupamentos e sumarização:** cálculo da emissão total por estado e por setor.  
- **Cálculo da emissão per capita:** divisão da emissão total pela população local.  
- **Visualizações:**  
  - Gráfico de dispersão (População × Emissão)  
  - Gráfico de barras (Emissão per capita por estado)  
  - Gráfico de bolhas (População, Emissão e Emissão per capita combinados)  

---

## Principais Descobertas
- Estados mais populosos geralmente emitem mais gases, porém nem sempre de forma proporcional.  
- Alguns estados com menor população apresentam alta emissão per capita, indicando a influência de fatores como os setores industrial e agropecuário.  
- A análise per capita é essencial para identificar impactos ambientais desproporcionais entre os estados.  

---

## Como Visualizar o Projeto
Você pode abrir o notebook diretamente pelo [nbviewer](https://nbviewer.org/) ou clonar o repositório e abrir localmente:

```bash
git clone https://github.com/seu-usuario/nome-do-repo.git
cd nome-do-repo
jupyter notebook
