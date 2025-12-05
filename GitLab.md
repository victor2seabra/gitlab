# Runners

Se tratam de softwares que, ao chamarmos Jobs dentro de um pipeline, realizam a execução do Job em questão

Podemos ter diferentes tipos:

## Shared
são runners que são disponíveis para todos os projetos dentro de uma instancia do GitLab

## Group
são runners que estão disponíveis para projetos de mesmo grupo

## Project
são runners especificos para cada projeto

# GitLab Runner Executor
Define o ambiente em que o Job será executado

![[Pasted image 20251029150638.png]]

Temos por exemplo:
* Hypervisor de uma VM
* Shell
* Remote SSH
* Docker
* Kubernetes
* Executor personalizado
# Monitoramento
Possui de modo integrado um controle e acompanhamento de métricas via Prometheus usando protocolo HTTP
# Tags
Podemos usar Tags para identificar Runners para tornar mais simples nosso manuseio e designação de qual Runner deve executar um dado Job
