# Envio Automático de Mensagens

Este projeto contém um código simples em Python para envio automatizado de mensagens.

## Como funciona
- Lê uma base de dados (.xlsx)
- Automatiza o envio das mensagens para os contatos listados

## Como usar
1. Clone este repositório
2. Abra o notebook `envio_automatico.ipynb`
3. Execute as células conforme as instruções

## Requisitos

- Python 3.x
- Navegador Google Chrome instalado
- [ChromeDriver](https://chromedriver.chromium.org/) compatível com a versão do seu Chrome (adicione o executável no PATH ou na mesma pasta do projeto)
- Jupyter Notebook ou JupyterLab (se for rodar o `.ipynb`)

### Bibliotecas Python utilizadas

- selenium
- pandas
- openpyxl (caso seu arquivo Excel seja .xlsx)
- urllib
- time
- traceback

#### Instalação das bibliotecas

Execute no terminal:

```bash
pip install selenium pandas openpyxl
