<h1 align="center">AJUSTE DE DADOS PLUVIOMÉTRICOS </h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-ativo-success" />
  <img src="https://img.shields.io/badge/python-3.10%2B-blue" />
  <img src="https://img.shields.io/badge/interface-Kivy-orange" />
  <img src="https://img.shields.io/badge/licença-MIT-green" />
</p>

---
🌧️ AJUSTE DE DADOS PLUVIOMÉTRICOS
📌 Sobre o projeto

Esta ferramenta foi desenvolvida para auxiliar no tratamento de dados pluviométricos disponibilizados pelo CEMADEN (Centro Nacional de Monitoramento e Alertas de Desastres Naturais).

Os dados obtidos pelo Mapa Interativo do CEMADEN são fornecidos em formato CSV com resolução horária, o que exige processamento adicional para análises em escalas maiores.

A aplicação automatiza esse processo, permitindo a geração de dados agregados em diferentes escalas temporais:

📅 Diário
📊 Semanal
🗓️ Mensal

<h2>🧠 Funcionalidades</h2>

<ul>
  <li>Processamento automático de dados horários</li>
  <li>Agregação temporal (diário, semanal e mensal)</li>
  <li>Interface gráfica simples</li>
  <li>Modo individual e em lote</li>
  <li>Feedback de execução (sucesso/erro)</li>


# 🖼️ Interface
 
 # AJUSTE DE DADOS PLUVIOMÉTRICOS – Multi
  
A versão Multi permite o processamento em lote de diversos arquivos CSV simultaneamente.

<img width="790" height="344" alt="01" src="https://github.com/user-attachments/assets/f8e56871-2c3f-48f2-8b1b-e8cb524d9e3c" />

## Funcionamento:

PASSO 1 - O usuário seleciona a pasta onde estão armazenados os arquivos CSV baixados.

PASSO 2 - O usuário define a pasta de destino onde serão salvos os resultados processados.

<img width="776" height="313" alt="image" src="https://github.com/user-attachments/assets/3d2bab0f-97eb-47f1-8039-6ecf1a7ccad3" />

Ao executar o processamento, o programa realiza automaticamente o somatório dos dados e gera novos arquivos com agregações por valor DIÁRIO, SEMANAL e MENSAL.

<img width="580" height="199" alt="image" src="https://github.com/user-attachments/assets/2fe0573e-8a13-462b-9551-ee5be4439800" />

Caso ocorra algum erro durante o processo ou ao final da execução, a aplicação exibe mensagens informativas de status (sucesso ou falha).
  
  
# AJUSTE DE DADOS PLUVIOMÉTRICOS – Single
  
  
A versão Single permite o processamento individual de um único arquivo CSV.

<img width="776" height="333" alt="image" src="https://github.com/user-attachments/assets/bace5c52-3a4f-46dd-8d21-bf87365bf478" />

## Funcionamento:

PASSO 1 - O usuário seleciona o arquivo CSV desejado.

PASSO 2 - O usuário define a pasta onde os resultados serão salvos.

<img width="780" height="313" alt="image" src="https://github.com/user-attachments/assets/b5f17235-18fe-41b1-ad76-30bf76cdd1a5" />

Ao executar o processamento, o programa gera dados agregados (diário, semanal e mensal).

<img width="576" height="207" alt="image" src="https://github.com/user-attachments/assets/8beed1a1-6cd7-4591-a0c8-d51cae1e23c0" />

## 📦 Executável (.exe)

Você pode baixar a versão pronta do programa:

🔗 https://drive.google.com/drive/folders/1e9yWfYiQKLLxBoP38zqWhKGlab75TCDU?usp=sharing

Após o download: Execute diretamente


# Observação
A ferramenta foi pensada para otimizar fluxos de trabalho em análises hidroclimáticas, reduzindo o tempo gasto com manipulação manual de dados horários e permitindo maior foco na interpretação geográfica e climatológica dos resultados.


