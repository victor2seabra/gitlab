# Runners
São aplicações que executam para nós o pipeline de CI/CD

Cada usuário pode acessar e criar esses runners (**VER COMO GERENCIAR ISSO COM PERMISSÕES**)
# Jobs
Se tratam de tarefas executadas pelo pipeline 

Cada Job tem um nome único e um script

Quando um script finaliza, outro é acionado, se assim configurado
# Stages
Se trata de uma abstração que envolvem os Jobs

Garantem que os Jobs sejam finalizados
# Pipeline
Se trata do conjunto de Stages onde cada Stage tange um ou mais Jobs