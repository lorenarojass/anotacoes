# anotacoes

Jira
Gitlab
Kubernetes
Rancher
Dba,DBRE
Plataform ouwner, PO
Tech lead
Sre
Devops

Ambientes:
    Producao
    Desenvolvimento
    Seandbox=testar codigos

Daily
Malwares
Secret
CI/CD
Datadog
Readme

Terraform: conrola a infraestrutura
Gitlab CI: constroi e testa
Argo CD: faz deploy gitOps para kubernetes

***STAGES***
BUILD
TEST
DEPLOY
JOBS

Git: sistema que registra mudanças no código, permitindo voltar no tempo e trabalhar em equipe.

Commit: registro de alterações no código com mensagem, data e autor.

Branch: versão paralela do código, usada para desenvolver funcionalidades sem afetar o principal.

Merge / Merge Request (MR): juntar mudanças de uma branch na branch principal.

Push: enviar commits locais para o repositório remoto.

Pull: trazer alterações do repositório remoto para o seu computador.

Pipeline: sequência de etapas automáticas para compilar, testar, empacotar e entregar o código.

Stage: fase do pipeline (ex: build, test, deploy).

Job: tarefa específica dentro de um stage do pipeline.

Controle de versão e Git

Git: sistema que registra mudanças no código, permitindo voltar no tempo e trabalhar em equipe.

Commit: registro de alterações no código com mensagem, data e autor.

Branch: versão paralela do código, usada para desenvolver funcionalidades sem afetar o principal.

Merge / Merge Request (MR): juntar mudanças de uma branch na branch principal.

Push: enviar commits locais para o repositório remoto.

Pull: trazer alterações do repositório remoto para o seu computador.

Pipeline: sequência de etapas automáticas para compilar, testar, empacotar e entregar o código.

Stage: fase do pipeline (ex: build, test, deploy).

Job: tarefa específica dentro de um stage do pipeline.

Gerenciamento de projetos

Jira: ferramenta para organizar tarefas e projetos, muito usada em times ágeis.

Issue: tarefa ou bug registrado no Jira.

Epic: conjunto de tarefas grandes que podem ser divididas em issues menores.

Subtask: tarefa menor dentro de uma issue.

Board: quadro que mostra o status das tarefas (ex: Kanban ou Scrum).

Sprint: período curto de trabalho para completar um conjunto de tarefas.

Burndown / Velocity: métricas de progresso de um sprint.

Containers e Docker

Container: pacote que contém uma aplicação e todas suas dependências, isolado do sistema.

Docker: ferramenta para criar e gerenciar containers.

Imagem: modelo do container (receita).

Container em execução: a imagem rodando (prato pronto).

Dockerfile: arquivo que descreve como criar a imagem do container.

Orquestração e Kubernetes

Kubernetes (K8s): sistema que gerencia containers em múltiplos servidores, garantindo alta disponibilidade e escalabilidade.

Cluster: conjunto de servidores (nodes) que formam o Kubernetes.

Node: máquina física ou virtual que roda containers.

Pod: menor unidade do Kubernetes; pode conter um ou mais containers.

Deployment: define como os pods são criados, atualizados e escalados.

Service: define como expor os pods para a rede interna ou externa.

Namespace: separação lógica dentro do cluster para organizar recursos.

GitOps e Argo CD

GitOps: prática de usar Git como “fonte da verdade” para deploy e configuração.

Argo CD: ferramenta GitOps que mantém o estado do Kubernetes sincronizado com o Git.

Sync / Sincronização: atualizar o cluster para que fique igual ao Git.

Rollback: reverter para uma versão anterior da aplicação ou configuração.

Rancher

Rancher: plataforma que gerencia múltiplos clusters Kubernetes de forma centralizada.

Multi-cluster management: gerenciar vários clusters ao mesmo tempo.

RBAC (Role-Based Access Control): controle de permissões baseado em funções.

App Catalog: catálogo de aplicativos para deploy rápido via Helm ou GitOps.

Outros termos importantes

CI/CD: Continuous Integration / Continuous Delivery (integração e entrega contínua).

Deploy / Deployment: colocar a aplicação em produção ou em um ambiente acessível.

Helm / Helm Chart: ferramenta para gerenciar pacotes de Kubernetes.

Manifest / YAML: arquivo que descreve a configuração de aplicações no Kubernetes.

Microserviço: aplicação dividida em partes pequenas e independentes.

💡 Resumo geral:
Cada palavra que você viu se conecta em um fluxo moderno de desenvolvimento:

Git / GitLab / Jira → escrever e organizar o código e tarefas.

Docker / Container → empacotar aplicações.

Kubernetes → rodar containers de forma escalável.

Argo CD / GitOps → automatizar deploy via Git.

Rancher → gerenciar vários clusters e aplicações centralizadamente.

    
