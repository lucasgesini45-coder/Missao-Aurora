 🚀 MISSÃO AURORA SIGER

📌 Sobre o Projeto
A MISSÃO AURORA SIGER é um sistema desenvolvido em Python que simula o processo de verificação, análise e autorização para o lançamento de um foguete.
O projeto integra simulação de telemetria, análise energética e inteligência artificial, criando um fluxo completo de decisão semelhante a sistemas reais de pré-decolagem.

⚙️ Funcionalidades

🔍 Telemetria Simulada

Geração de dados críticos:

	•	Temperatura interna e externa
	
	•	Níveis de energia
	
	•	Pressão dos tanques
	
	•	Integridade estrutural
	
	•	Status dos módulos

📊 Exibição em tabela com Pandas

⚡ Análise Energética

Cálculo de:

	•	Capacidade total
	
	•	Energia disponível
	
	•	Perdas
	
	•	Consumo na decolagem
	
	•	Autonomia
	
Resultado:

	•	✅ OK
	
	•	⚠️ Crítico

🧠 Inteligência Artificial
Uso de Scikit-learn com modelo de Árvore de Decisão para prever a segurança do lançamento.
Saída:

	•	✔️ Seguro
	
	•	❌ Não seguro

🚦 Decisão Final

A lógica do sistema:

IA = OK  AND  Energia = OK  → 🚀 Lançamento autorizado

Caso contrário              → ❌ Lançamento cancelado

🛠️ Tecnologias

	•	Python
	
	•	Pandas
	
	•	NumPy
	
	•	Scikit-learn

📊 Exemplo de Saída

Telemetria:

Temperatura Interna: 22°C

Temperatura Externa: 16°C

Energia: 87%

Pressão: 95%

Integridade: 1

Módulos: OK

Relatório Energético:

Energia disponível: 75%

Consumo estimado: 60%

Status: OK

IA: Lançamento Seguro

>>> RESULTADO FINAL:   AUTORIZADO >>>

🚀 Como Executar

git clone https://github.com/lucasgesini45-coder/Missao-Aurora.git

cd aurora-siger

pip install -r requirements.txt

python main.py

📁 Estrutura Sugerida

aurora-siger/

├── main.Ipynb

├── telemetria.ipynb

├── energia.ipynb

├── ia_modelo.ipynb

├── requirements.txt

└── README.md

🎯 Objetivo

Este projeto tem como foco demonstrar na prática:

	•	Simulação de sistemas complexos
	
	•	Análise de dados
	
	•	Tomada de decisão automatizada
	•	Aplicação de Machine Learning
