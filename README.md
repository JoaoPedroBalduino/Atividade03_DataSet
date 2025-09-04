# Atividade 03 – Tratamento e Análise de Dados

Este projeto consiste em um notebook desenvolvido para a disciplina de **[inserir nome da disciplina]**, cujo objetivo é realizar o **pré-processamento, limpeza e análise exploratória** de um conjunto de dados fornecido em formato Excel.  

## 📌 Objetivos  
- Ler e inspecionar o dataset inicial.  
- Identificar e tratar **valores nulos**.  
- Detectar e remover **valores duplicados**.  
- Corrigir e padronizar dados inconsistentes.  
- Converter colunas para os **tipos de dados adequados**.  
- Gerar **gráficos exploratórios** para análise visual.  

## 🛠️ Tecnologias Utilizadas  
- [Python 3](https://www.python.org/)  
- [Pandas](https://pandas.pydata.org/)  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  

## 📂 Estrutura do Projeto  
```
Atividade03.ipynb        # Notebook principal com o passo a passo
atividade3_dataset.xlsx  # Dataset utilizado (colocar na raiz do projeto)
```

## 🚀 Como Executar  
1. Clone o repositório:  
   ```bash
   git clone https://github.com/usuario/repositorio.git
   cd repositorio
   ```
2. Instale as dependências necessárias:  
   ```bash
   pip install pandas numpy matplotlib
   ```
3. Certifique-se de ter o arquivo `atividade3_dataset.xlsx` na pasta raiz.  
4. Abra o Jupyter Notebook:  
   ```bash
   jupyter notebook Atividade03.ipynb
   ```

## 📊 Principais Processamentos  
- Conversão da coluna `Preço` para valores numéricos.  
- Preenchimento dos valores nulos com a **mediana**.  
- Conversão da coluna `Data_Compra` para o tipo `date`.  
- Padronização de valores na coluna `Cidade`.  
- Criação de gráficos para análise de correlação e distribuição.  

## 👨‍💻 Autor  
Projeto desenvolvido por **[Seu Nome]**.  
