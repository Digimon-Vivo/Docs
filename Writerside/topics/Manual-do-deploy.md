# 🍉 Manual do deploy


> **Nota**
>
> Este guia descreve o processo para realizar o deploy de uma aplicação de forma segura e eficiente. Ele abrange desde a
preparação do ambiente até a finalização do deploy em produção, incluindo boas práticas e ferramentas recomendadas.
>O deploy pode ser realizado apenas após a Branch com as alterações ser mergeada na Master
> {style="note"}

• Passo 1: Clique em Pipelines

![passo 1](../images/guia_deploy/passo1.png)

• Passo 2: Busque pelo Repositório que será feito o deploy

![passo 2](../images/guia_deploy/passo2.png)

• Passo 3: Clique no Repositório referente ao micro-frontend

![passo 3](../images/guia_deploy/passo3.png)

• Passo 4: Clique em Run Pipeline

![passo 4](../images/guia_deploy/passo4.png)

• Passo 5: Preencha conforme o ambiente em que será feito o Deploy

![passo 5](../images/guia_deploy/passo5.png)

*Obs: as opções a baixo podem ser deixadas no padrão*

![obs_deploy.png](obs_deploy.png)

## Como obter o numero da versão ?

O numero da versão anterior pode ser encontrado na no arquivo "Package.json" na master:

![package_json_version.png](package_json_version.png)

Ou observando o numero da ultima versão que foi feito o Deploy.

Então basta contar as ultimas alterações a partir do ultimo deploy, e definir a próxima:

![pipe_version.png](pipe_version.png)

Para subir pra ambiente como pre-prod ou darklauncher precisa marcar para pula criação somente

![choose_environment.png](choose_environment.png)