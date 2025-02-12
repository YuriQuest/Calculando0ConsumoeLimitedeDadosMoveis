# Calculando Consumo e Limite de Dados Móveis

## Primeiro projeto | Cálculo de Consumo de Dados Móveis
### Descrição
Você foi contratado por uma empresa de telecomunicações para desenvolver um sistema que calcule o consumo total de dados móveis de um cliente durante um mês. O consumo semanal de dados móveis é fornecido como entrada. Além de calcular o total de dados consumidos no mês, o sistema deve fornecer uma média semanal de consumo e identificar a semana de maior consumo.

### Entrada
A entrada do programa é uma string com uma lista de valores representando o consumo semanal de dados em megabytes (MB), separados por vírgulas. Cada valor na lista corresponde ao consumo total de uma semana.

### Saída
A saída do programa deve incluir:

1. O consumo total de dados móveis em MB ao longo do mês.
2. A média semanal de consumo de dados móveis.
3. A semana de maior consumo (considerando o primeiro valor como o da semana 1).

Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

Entrada|	Saída
--|--
2064,4000,2000,3200	|Total mensal: 11264 MB - Media semanal: 2816 MB - Maior consumo: Semana 2
5000,4880,4600,6000	|Total mensal: 20480 MB - Media semanal: 5120 MB - Maior consumo: Semana 4
4000,4456,6000,5000	|Total mensal: 19456 MB - Media semanal: 4864 MB - Maior consumo: Semana 3

## Segundo projeto | Verificação de Limite de Dados Móveis
### Descrição
Desenvolva um sistema para monitorar o consumo mensal de dados móveis de clientes, verificando se excede o limite do plano adquirido. O sistema deve comparar o limite mensal, recebido em gigabytes (GB), com o consumo total de dados acumulado até o momento, fornecido em megabytes (MB). Se o consumo total ultrapassar o limite mensal, o sistema deverá informar ao cliente para adquirir ou renovar o pacote; caso contrário, deve retornar quanto em megabytes (MB) ainda está disponível para uso no mês.

### Entrada
A entrada do programa é fornecida em duas linhas:

A primeira linha contém o limite mensal de dados em gigabytes (GB).
A segunda linha contém o consumo total de dados móveis em megabytes (MB).
Saída
Dever

### Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

Entrada 1 | Entrada 2	|Saída
--|--|--
10 | 11264	|Limite de dados excedido. Compre ou renove seu pacote.
25 | 20480	|Voce ainda possui 5120 MB disponiveis.
20 | 19456	|Voce ainda possui 1024 MB disponiveis.