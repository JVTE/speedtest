# 🚀 SpeedTest App

Uma aplicação web simples para testar a velocidade da sua conexão com a internet, desenvolvida em Python com Streamlit.

## 📋 Descrição

Este projeto utiliza a biblioteca **Streamlit** para fornecer uma interface gráfica acessível via navegador, permitindo que usuários realizem testes de velocidade de internet de forma prática e visual. Ele usa a biblioteca **speedtest-cli** para realizar as medições.

## 🛠 Tecnologias Utilizadas

- **Python 3**
- [Streamlit](https://streamlit.io/)
- [speedtest-cli](https://github.com/sivel/speedtest-cli)
- [PyInstaller (opcional)](https://www.pyinstaller.org/) – para gerar executável (.exe)

## ⚙️ Funcionalidades

- Interface web simples e intuitiva.
- Botão para iniciar o teste de velocidade.
- Medição da velocidade de **download** e **upload** (em Mbps).
- Medição da **latência (ping)** em milissegundos.
- Barras de progresso para visualização da performance da conexão.

## 📸 Interface (ao rodar)

- Título: "SpeedTest"
- Instrução: "Clique no botão abaixo para iniciar o teste"
- Botão: "Iniciar"
- Resultados exibidos com texto e barras de progresso.

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/speedtest-app.git
   cd speedtest-app
