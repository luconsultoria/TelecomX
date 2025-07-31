📊 Análise de Churn - TelecomX
Este projeto tem como objetivo analisar os dados de churn (evasão de clientes) da empresa fictícia TelecomX. Através de dados extraídos de uma API, realizamos transformações, limpeza, visualizações e análises exploratórias para identificar os principais fatores que influenciam a evasão de clientes e propor estratégias para aumentar a retenção.

🚀 Propósito da Análise
A evasão de clientes (churn) é um dos maiores desafios em negócios de assinatura. Este projeto visa:
•	Identificar os principais padrões de comportamento dos clientes que cancelaram os serviços.
•	Gerar insights para a criação de estratégias eficazes de retenção.
•	Visualizar correlações entre variáveis e a evasão.
•	Propor recomendações práticas com base na análise dos dados.

🗂️ Estrutura do Projeto
📁 telecom-churn-analysis/
│
├── 📄 README.md                ← Este arquivo
├── 📓 churn_analysis.ipynb     ← Notebook principal da análise
├── 📁 data/                    ← Diretório opcional para armazenar dados locais (caso deseje)
│   └── raw_data.json          ← Dados brutos da API (simulado ou real)
├── 📊 imagens/                 ← (Opcional) Gráficos exportados para uso em relatórios
└── requirements.txt           ← Dependências do projeto

🧪 Tecnologias Utilizadas
•	Python 3.x
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Jupyter Notebook

📈 Insights Obtidos
1. Distribuição do Churn
•	Aproximadamente 26,5% dos clientes abandonaram o serviço.

2. Contrato x Churn
•	Clientes com contrato "Month-to-month" são os mais propensos a cancelar.

3. Forma de Pagamento x Churn
•	Pagamentos via Electronic check estão fortemente ligados ao churn.

4. Tenure (Tempo de Contrato)
•	Clientes com menos de 12 meses de contrato têm alta propensão ao churn.

5. Tipo de Internet
•	Usuários de Fiber optic possuem maior taxa de evasão em comparação com outros tipos de conexão.

🔍 Principais Insights
•	Contratos mensais são mais suscetíveis à evasão.
•	Clientes recentes (tenure baixo) tendem a abandonar o serviço.
•	Electronic check é um sinal de risco de churn.
•	Ausência de serviços adicionais impacta negativamente na permanência dos clientes.

📌 Recomendações Estratégicas
•	Criar campanhas de fidelização para novos clientes.
•	Oferecer descontos em contratos anuais ou bienais.
•	Incentivar mudança na forma de pagamento de electronic check para opções mais seguras.
•	Promover serviços adicionais como suporte técnico e segurança online.
•	Desenvolver um sistema preditivo de churn para ações preventivas.

⚙️ Como Executar o Projeto
✅ Pré-requisitos
•	Python 3.7 ou superior instalado
•	pip para instalação de pacotes

🔧 Instalação
1.	Clone o repositório:
git clone https://github.com/seu-usuario/telecom-churn-analysis.git
cd telecom-churn-analysis
2.	Crie um ambiente virtual (opcional, mas recomendado):
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
3.	Instale as dependências:
pip install -r requirements.txt

▶️ Execução do Notebook
Abra o Jupyter Notebook com:
jupyter notebook
Em seguida, abra o arquivo churn_analysis.ipynb e execute célula por célula.
Observação: certifique-se de que o arquivo raw_data.json esteja acessível (ou simule os dados conforme descrito no notebook).

📎 Requisitos (requirements.txt)
pandas
numpy
matplotlib
seaborn
jupyter

🤝 Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
