---
sidebar_position: 2
---

# Dicionário de Dados

Detalhamento dos tipos de dados usados na agenda.

## Entidade: agenda_usuario

|Atributo|Classe|Domínio|Tamanho|Descrição|
|---|---|---|---|---|
|usuario_id|Determinante|Numérico|   |Incremental, gerado pelo banco de dados ao realizar o cadastro do usuário.|
|usuario_nome|Simples|Texto|100|Deve ser o nome real do usuário, não aceitando caracteres especiais, além dos utilizados pela língua portuguesa.|
|usuario_email|Simples|Texto|100|Deve seguir os padrôes de email (@sufixo.com)|
|usuario_status|Simples|Numérico|   |Indica se o usuário está ativo (0) ou inativo (1)|
|usuario_senha|Simples|Texto|10|Padrão por livre escolha do usuário.|

## Entidade: agenda_evento

|Atributo|Classe|Domínio|Tamanho|Descrição|
|---|---|---|---|---|
|evento_id|Determinante|Numérico|   |Incremental, gerado pelo banco de dados ao realizar o cadastro do evento.|
|evento_data_hora|Simples|Data||Deve seguir os padrões do tipo DATETIME.|
|evento_descricao|Simples|Texto|200|Deve conter as descrições e detalhamentos de um evento.|
|evento_nome|Simples|Texto|100|Indica o título do evento.|
|evento_status|Simples|Numérico||Indica se aquele evento está ativo ou não.|
|usuario_id|Simples|Numérico||Indica o usuário que é dono daquele evento.|