# 🚢 Análise de Sobrevivência do Titanic


*Este projeto é a minha primeira análise de dados exploratória, desenvolvida para aplicar e demonstrar minhas habilidades em Python na resolução de um problema histórico e fascinante.*

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Seaborn-882255?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn">
</div>

---

## O Desafio 

O naufrágio do Titanic é um dos eventos mais famosos da história. A narrativa popular diz que a prioridade de resgate foi para "mulheres e crianças". O desafio deste projeto foi usar o conjunto de dados real dos passageiros para verificar se essa e outras narrativas são confirmadas pelos fatos, respondendo a perguntas como:

- O status socioeconômico (classe do passageiro) realmente influenciou na chance de sobreviver?
- A política de "mulheres e crianças primeiro" é visível nos dados?
- Como a idade se relaciona com a probabilidade de sobrevivência?

---

## Minha Abordagem 

Para responder a essas perguntas, segui um processo estruturado de análise de dados:

1.  **Limpeza e Preparação:** Carreguei os dados com Pandas e realizei a limpeza, tratando dados faltantes (especialmente na coluna de idade) para garantir a integridade da análise.
2.  **Análise Exploratória:** Usei o poder do Pandas para agrupar, fatiar e cruzar os dados, calculando taxas de sobrevivência para diferentes segmentos de passageiros.
3.  **Visualização de Dados:** Criei gráficos com Matplotlib e Seaborn para visualizar as descobertas, tornando os padrões e as conclusões fáceis de entender.

---

## Conclusões e Insights 📈

A análise dos dados permitiu extrair conclusões claras:

- ✅ **Status Social foi Crucial:** Passageiros da 1ª classe tiveram uma taxa de sobrevivência de ~63%, muito superior aos ~24% da 3ª classe.
- ✅ **Mulheres Tiveram Prioridade:** Cerca de 74% das mulheres a bordo sobreviveram, em contraste com apenas ~19% dos homens.
- ✅ **Crianças Foram Protegidas:** Os gráficos mostram um pico notável na taxa de sobrevivência para crianças abaixo de 10 anos.

Os dados não mentem: a narrativa histórica é, em grande parte, confirmada pela análise.

---

## Como Rodar o Projeto 🚀

Para explorar a análise por conta própria:

1.  Clone este repositório: `git clone https://github.com/XkosmichX/Analise-Dados-titanic.git`
2.  Instale as dependências necessárias (Pandas, Matplotlib, Seaborn).
3.  Execute o Jupyter Notebook `analise_titanic.ipynb`.
