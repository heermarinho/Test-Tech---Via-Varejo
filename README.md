# Test Tech MLOps
----

## Desafio

Neste desafio teremos 2 etapas fundamentais para concluir esste test.
Duração: até 6 dias
PS: Ambas as etapas devem ser seguidas, mas tambem existe margem para alterações, caso o candidato queira trocar a arqutietura, fica aberto para a mesma. De qualquer forma e indispensavel o uso das técnologias como K8S, Metabase e MongoDB

### 1 Etapa  (API REST) 🔌

Nessa desafio você precisa desenvolver uma api rest seja a porta de entrada para um grande volume de dados, tendo como ENDPOINT e rota abaixo 

exemplo: -> [POST] ingress.api-mlops-via.com  /api/v1/telemetria/ 

URL   | ENDPOINT | TIPO 
--------- | ------ | ----- 
ingress.domain-free.com.br | /api/v1/telemetry | POST


PARAMETRO   | TIPO 
--------- | ------ 
MODEL_NAME | STRING
VERSION | STRING 
METRICS | DICT 

EXEMPLO: 

PARAMETROS DE ENTRADA {'MODELO':'churn', 'VERSION': '1.0', 'METRICA':{"ACC": 0.8, "AUC": 0.6}}

Essa aplicação precisa ter os seguintes requisitos minimos de arquivos(dockerfile, app.py e requirements.txt, README.md)


### 2 Etapa  (Infra as Code) 🛠
Com base na imagem abaixo use seus conhecimentos em infra como codigo para provisionar essa estrutura para comportar seus codigos da proxima etapa

- > K8S - https://kubernetes.io/pt-br/

- > Banco de Dados - https://www.mongodb.com/pt-br

- > Telemetria - https://www.metabase.com/

Essa aplicação precisa ter os arquivos de configuração do terraform

## Arquitetura PROPOSTA 🖥
 
 ![](https://raw.githubusercontent.com/heermarinho/Test-Tech---Via-Varejo/main/5874a6bb-f8e7-4838-8c52-9e888ab0369e%20(1).png?token=ATB2NS6PA7KZ75IYX6NMJJDBJSO6U)

## OBJETO DE AVALIAÇÃO ✅

ETAPA   | OBJETIVO 
--------- | ------ 
1 | QUALIDADE DO CODIGO 
1 | ARQUITETURA LIMPA E DOCUMENTAÇÃO CLARA 
2 | QUALIDADE DE CODIGO
2 | DOCUMENTAÇÃO CLARA  

---- 
