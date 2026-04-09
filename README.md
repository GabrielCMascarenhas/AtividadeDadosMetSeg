# Projeto de Integração de Dados de Criminalidade e Meteorologia em Passo Fundo

## Integrantes do Grupo
- Felipe Roberto Bacchi
- Gabriel Mascarenhas
- Lauro Dariva Ferneda
- Pedro Souza
- Pedro Tronco

---

## Descrição
Este projeto tem como objetivo realizar a coleta, organização, tratamento, integração e análise de dados de **criminalidade** e **meteorologia** no município de **Passo Fundo (RS)**.

A proposta do trabalho envolve a construção de um pipeline de dados utilizando **Python** e **Google Colab**, permitindo que todos os integrantes do grupo possam trabalhar de forma colaborativa sobre a mesma base de dados.

---

## Objetivos do Projeto
- Coletar e organizar os datasets de criminalidade e meteorologia;
- Padronizar e limpar os dados;
- Integrar os datasets com base em **data** e **município**;
- Preparar uma base final tratada para futuras análises;
- (Opcional) Explorar padrões e relações entre clima e criminalidade.

---

---

## O que o arquivo `.ipynb` faz
O notebook `.ipynb` realiza todo o pipeline do projeto: leitura dos arquivos originais de criminalidade e meteorologia, inspeção inicial das bases, padronização de colunas, tratamento de valores ausentes, remoção de duplicatas, ajuste de formatos de data, filtragem do município de **Passo Fundo**, integração entre as bases por **data** e **cidade**, tratamento de inconsistências e transformações finais para gerar um dataset limpo, estruturado e pronto para análise exploratória.

---

## Resultados Finais do Trabalho
Como resultado, foi gerado um **dataset final tratado**, contendo variáveis de **ocorrências criminais** e **condições meteorológicas** para o município de **Passo Fundo**, permitindo futuras análises sobre possíveis relações entre clima e criminalidade. O projeto também resultou em uma estrutura organizada de dados, um processo reprodutível no Google Colab e arquivos finais exportados em formato `.csv`.

---

## Estrutura de Pastas

```bash
projeto_criminalidade_passo_fundo/
│
├── data/
│   ├── raw/
│   │   ├── data_criminalidade/
│   │   └── data_meteorologia/
│   │
│   ├── interim/
│   └── processed/
│
├── notebooks/
├── outputs/
│   ├── graficos/
│   └── tabelas/
│
├── docs/
├── README.md
└── requirements.txt
```

---

## Organização dos Dados

### Dados de criminalidade
Os dados de criminalidade estão armazenados em:

```bash
data/raw/data_criminalidade/
```

Arquivo principal utilizado:

```bash
criminalidade_ocorrencias_rs_2026.csv
```

---

### Dados meteorológicos
Os dados meteorológicos estão armazenados em:

```bash
data/raw/data_meteorologia/
```

Arquivo principal utilizado para o projeto:

```bash
PASSO_FUNDO_2021-01-01_2025-09-05.csv
```

Arquivos meteorológicos de localidades próximas também foram mantidos para apoio e possível comparação.

---

## Ferramentas Utilizadas
- Python
- Google Colab
- Pandas

---

## Etapas do Projeto
1. Coleta e organização dos dados
2. Concatenação/unificação dos dados de criminalidade
3. Limpeza e padronização
4. Integração com dados meteorológicos
5. Transformações e preparação final dos dados
6. (Opcional) Exploração e descoberta

---

## Observações
- O projeto foi estruturado para ser executado em ambiente colaborativo no **Google Colab**.
- Todos os integrantes do grupo devem conseguir rodar o notebook individualmente.
- A base de criminalidade será filtrada posteriormente para o município de **Passo Fundo**.
