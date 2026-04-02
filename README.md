Python-Insights: Análise de Dados e Churn

Este projeto utiliza Python para realizar uma análise exploratória de dados em uma base de clientes, com o objetivo de identificar os principais motivos de cancelamento e sugerir estratégias para aumentar a retenção.

🚀 Funcionalidades
Tratamento de Dados: Limpeza de valores vazios e remoção de colunas irrelevantes.

Análise Estatística: Cálculo das taxas de cancelamento atuais.

Visualização de Dados: Geração de gráficos comparativos para identificar padrões entre clientes ativos e cancelados.

Geração de Insights: Diagnóstico de problemas específicos em serviços, formas de pagamento e duração de contratos.

🛠️ Tecnologias Utilizadas
Python 3.x

Pandas: Para manipulação e análise de dados.

Plotly Express: Para criação de gráficos interativos.

📋 Pré-requisitos
Antes de começar, você precisará ter o Python instalado em sua máquina. Além disso, as seguintes bibliotecas são necessárias:

Bash
pip install pandas plotly openpyxl
🔧 Como Executar
Clone o repositório:

Bash
git clone https://github.com/michaellekim/Python-Insights.git
Navegue até o diretório do projeto.

Certifique-se de que a base de dados (telecom_users.csv ou similar) está na mesma pasta que o script.

Execute o script:

Bash
python main.py

📊 Exemplo de Insights Obtidos
Durante a análise, observamos pontos críticos como:

Contratos Mensais: Clientes com contrato mensal possuem uma taxa de cancelamento significativamente maior.

Serviço de Fibra Óptica: Clientes que utilizam fibra apresentam mais reclamações/cancelamentos que os de ADSL.

Formas de Pagamento: O pagamento automático reduz drasticamente a evasão.

✒️ Autor
Michael Kim 
