---
sidebar_position: 3
---

# Casos de Uso NNN

Especificações dos Casos de Uso

### Caso de Uso 1
- Identificador: **1**
- Nome: **Fazer Login**
- Resumo: **O usuário deverá realizar um login**
- Ator: **Usuário**
- Prioridade: **Essencial**
- Requisitos não funcionais Associados: **Segurança/Confiabilidade**
- Pré-condições: **Cadastro do Usuário no sistema**
- Pós-condições: **Usuário Logado**
- Fluxo de eventos principal: **Ao iniciar o app, o usuário verá como primeira tela a realização de login, caso possua uma conta, apenas será necessário preencher os campos de email e senha para realizar o login.**
- Fluxos Secundários: **Caso ainda não possua uma conta, ou preencha algum dado de maneira errônea, o usuário receberá uma mensagem de erro.**

### Caso de Uso 2
- Identificador: **2**
- Nome: **Deslogar**
- Resumo: **O usuário deverá realizar logout**
- Ator: **Usuário**
- Prioridade: **Essencial**
- Requisitos não funcionais Associados: **Segurança/Confiabilidade**
- Pré-condições: **Login do Usuário no Sistema**
- Pós-condições: **Usuário deslogado**
- Fluxo de eventos principal: **Ao entrar nas configurações de conta, o usuário poderá visualizar a opção de realizar o logout, selecionando essa opção, o usuário sairá de sua conta.**
- Fluxos Secundários: **Após deslogar-se, o usuário deve ser redirecionado para a tela de login.**

### Caso de Uso 3
- Identificador: **3**
- Nome: **Manter Usuário**
- Resumo: **O Sistema deverá realizar o CRUD do usuário**
- Ator: **Usuário**
- Prioridade: **Essencial**
- Requisitos não funcionais Associados: **Segurança/Confiabilidade/Eficiência**
- Pré-condições: **Usuário sem conta no sistema**
- Pós-condições: **Usuário Cadastrado no Sistema**
- Fluxo de eventos principal: **Ao iniciar o app pela primeira vez, o usuário que não possui uma conta cadastrada deverá seguir a opção de cadastro exibida na tela de login, após isso, deverá preencher seus dados e submetê-los ao sistema, concluindo o cadastro.**
- Fluxos Secundários: **Caso o usuário digite algum dado inválido, uma mensagem de erro deverá ser exibida.**

### Caso de Uso 4
- Identificador: **4**
- Nome: **Visualizar Calendário**
- Resumo: **O usuário pode visualizar o calendário e trocar os meses**
- Ator: **Usuário**
- Prioridade: **Essencial**
- Requisitos não funcionais Associados: **Usabilidade/Eficiência**
- Pré-condições: **Usuário Logado no Sistema**
- Pós-condições: **Usuário utilizando as funções do calendário**
- Fluxo de eventos principal: **Estando logado no sistema, o usuário poderá utilizar as funções características do calendário.**

### Caso de Uso 5
- Identificador: **5**
- Nome: **Visualizar Dia**
- Resumo: **O usuário pode visualizar o calendário em formato de dias**
- Ator: **Usuário**
- Prioridade: **Essencial**
- Requisitos não funcionais Associados: **Usabilidade/Eficiência**
- Pré-condições: **Usuário Logado no Sistema**
- Pós-condições: **Usuário utilizando as funções do calendário para visualização de dias**
- Fluxo de eventos principal: **Estando logado no sistema, o usuário poderá utilizar as funções características do calendário em relação aos dias.**

### Caso de Uso 6
- Identificador: **6**
- Nome: **Manter Evento**
- Resumo: **O usuário pode realizar o CRUD de eventos em um ou mais dias do calendário.**
- Ator: **Usuário**
- Prioridade: **Essencial**
- Requisitos não funcionais Associados: **Usabilidade/Eficiência/Confiabilidade/Segurança**
- Pré-condições: **Usuário Logado no Sistema**
- Pós-condições: **Eventos devidamente cadastrados nos dias especificados pelo usuário.**
- Fluxo de eventos principal: **Estando logado no sistema, o usuário poderá realizar o CRUD de eventos nos dias desejados, para isso, deverá preencher os dados sobre o evento na tela de cadastro de eventos no dia específico.**
- Fluxos Secundários: **Caso o usuário digite algum dado inválido, uma mensagem de erro deverá ser exibida.**

### Caso de Uso 7
- Identificador: **7**
- Nome: **Notificar Evento**
- Resumo: **O usuário deve ser notificado caso algum evento esteja planejado para o dia atual.**
- Ator: **Usuário**
- Prioridade: **Essencial**
- Requisitos não funcionais Associados: **Usabilidade/Eficiência/Confiabilidade**
- Pré-condições: **Usuário Logado no Sistema e Eventos devidamente cadastrados nos dias especificados pelo usuário.**
- Pós-condições: **Usuário sendo notificado dos eventos atuais.**
- Fluxo de eventos principal: **Ao ter um evento atual, o usuário será notificado da data e do planejamento feito para o dia.**
- Fluxos Secundários: **O usuário poderá fechar a notificação quando quiser.**




