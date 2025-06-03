
# Projeto: ETL de Dados de Hospedagem com Python e Pandas

Este projeto realiza um processo completo de **ETL (Extração, Transformação e Carga)** com base em um arquivo JSON contendo dados brutos de hospedagens na cidade de Seattle. Utilizando Python e bibliotecas como `pandas`, o projeto trata dados não estruturados, extrai informações relevantes e organiza o conteúdo de forma limpa e utilizável para futuras análises.

---

## Base do Projeto

Este projeto foi desenvolvido como parte prática do curso:  
**"Domine a Análise de Dados: De Numpy e Pandas a Streamlit e Bancos de Dados, tudo com Python na prática!"**, ministrado por **Code TI**.

---

## Estrutura do Projeto

```
etl-hospedagem/
│
├── dados_hospedagem.json      # Fonte original de dados brutos (JSON)
├── manipula_dados.ipynb       # Notebook com todo o processo de ETL
├── hospedagens_tratadas.csv   # Arquivo final com dados limpos (gerado pelo notebook)
├── hospedagens_tratadas.xlsx   # Arquivo final com dados limpos (gerado pelo notebook)
└── README.md                  # Documentação do projeto
```

---

## Fluxo ETL

- **Extração**: leitura dos dados brutos a partir do arquivo JSON.
- **Transformação**:
  - Normalização da estrutura de dados aninhados.
  - Conversão de tipos e limpeza de colunas (ex.: avaliação, quantidade de hóspedes).
  - Filtragem e padronização textual.
- **Carga**: exportação para um novo arquivo CSV e do Excel contendo os dados limpos e estruturados.

---

## Como Executar

1. **Clone o repositório ou envie os arquivos ao seu GitHub**

2. (Opcional) Crie um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. **Instale as bibliotecas necessárias:**
   ```bash
   pip install pandas
   ```

4. **Abra e execute o notebook:**
   ```
   manipula_dados.ipynb
   ```

---

## Requisitos

- Python 3.7 ou superior
- Bibliotecas:
  - `pandas`
  - `json` (interna do Python)

---

## Autor

Desenvolvido por **Paulo Henrique P. Cunha**  
Analista de Dados
[GitHub](https://github.com/paulohenriquecunha)  
[LinkedIn](https://www.linkedin.com/in/paulohenriquepcunha)  

---

## Licença

Este projeto está licenciado sob a Licença MIT.
