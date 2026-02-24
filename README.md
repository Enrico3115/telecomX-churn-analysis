# 📡 Telecom X - Análise de Evasão de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## 🎯 Propósito do Projeto
A **Telecom X** enfrenta um desafio crítico: uma alta taxa de cancelamento de clientes (Churn). O objetivo deste projeto é atuar como uma consultoria de dados, analisando a base de clientes para responder a perguntas estratégicas:

* Quais são os principais fatores que levam à saída de clientes?
* Qual é o perfil do cliente propenso ao cancelamento?
* Quais ações podem ser tomadas para aumentar a retenção?

## 📂 Estrutura do Projeto

O repositório está organizado da seguinte forma:

```bash
telecomX-churn-analysis/
│
├── TelecomX_Parte1.ipynb    # Notebook principal (ETL + EDA + Relatório)
├── requirements.txt         # Lista de dependências do projeto
├── README.md                # Documentação do projeto
└── .gitignore               # Arquivos ignorados pelo versionamento

```

## ⚙️ Metodologia Aplicada

1. **Extração:** Consumo de dados via API e normalização de JSON.
2. **ETL (Extração, Transformação e Carga):** Limpeza de dados nulos, conversão de tipos e tratamento de strings vazias.
3. **Análise Exploratória (EDA):** Criação de visualizações para validar hipóteses de negócio.
4. **Storytelling:** Elaboração de recomendações estratégicas baseadas em dados.

## 📊 Principais Insights Visualizados

Abaixo estão os principais pontos descobertos durante a análise:

### 1. O Fator "Tipo de Contrato"

Identificamos que a modalidade de contrato é o maior divisor de águas.

**Conclusão:** Clientes com contratos mensais (*Month-to-month*) representam a esmagadora maioria das evasões. Contratos de 1 ou 2 anos geram fidelidade.

### 2. O Problema da Fibra Óptica

Analisando os serviços de internet, encontramos um padrão preocupante.

**Conclusão:** A taxa de rejeição da Fibra Óptica é significativamente maior do que o DSL, indicando possíveis problemas técnicos ou preço desajustado.

### 3. Clientes Novos vs. Antigos

**Conclusão:** O risco de churn é crítico nos primeiros 10 meses. Após esse período, a probabilidade de o cliente sair cai drasticamente.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Bibliotecas:**
* `Pandas` (Manipulação de dados)
* `Matplotlib` & `Seaborn` (Visualização)
* `Requests` (Integração com API)
* `Numpy` (Cálculo numérico)


* **Ambiente:** Jupyter Notebook

## 🚀 Como Executar o Projeto

Para reproduzir esta análise na sua máquina local:

1. **Clone o repositório:**
```bash
git clone [https://github.com/Enrico3115/telecomX-churn-analysis.git](https://github.com/Enrico3115/telecomX-churn-analysis.git)

```


2. **Entre na pasta:**
```bash
cd telecomX-churn-analysis

```


3. **Instale as dependências:**
```bash
pip install -r requirements.txt

```


4. **Execute o Notebook:**
```bash
jupyter notebook TelecomX_Parte1.ipynb

```



## ✒️ Autor

Desenvolvido por **Enrico Moreira Soares de Almeida**.

Entre em contato!

```
enrico311006@gmail.com
```
