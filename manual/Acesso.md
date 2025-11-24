# Necto / Projeto Neo Horizon

## 1. Sobre o Sistema

A Neo Horizon irá fornecer uma ferramenta analítica desenvolvida para gestão de projetos, produtividade e custos de equipes de desenvolvimento.
O sistema consolida dados de plataformas de gestão (como o Jira) em um Data Warehouse, apresentando gráficos e indicadores de desempenho para apoiar decisões estratégicas. Hospedado na AWS, o sistema é acessado via navegador, sem necessidade de instalação local.
O ambiente atual comporta até 200 usuários simultâneos, garantindo estabilidade para fins acadêmicos e operacionais.

## 2. Acesso ao Sistema

* **Endereço:** [Clique aqui](http://fatecneohorizon-alb-1039129083.us-east-1.elb.amazonaws.com)

**Acesso inicial:**

* Os usuários e as senhas iniciais serão enviados via canal seguro (Slack).
* Após o primeiro login, o administrador poderá cadastrar novos usuários diretamente no sistema, conforme as permissões configuradas.

**Tela de Login**

* Autenticação por usuário e senha.
* Acesso controlado por perfis de permissão (Administrador, Gerente, Desenvolvedor).

## 3. Interface e Navegação

A interface do Neo Horizon é composta por:

* **NavBar:** navegação entre dashboards e módulos de gerenciamento.
* **Área principal:** exibição dos dados e gráficos.
* **Filtros:** seleção de período, projeto e equipe.

## 4. Funcionalidades Entregues

| Módulo                           | Descrição                                                                       |
| -------------------------------- | ------------------------------------------------------------------------------- |
| Relatórios de Atividades e Horas | Relatórios diários, mensais e anuais por desenvolvedor e por projeto.           |
| Gerenciamento de Valor/Hora      | Controle de custo/hora por desenvolvedor, com edição restrita ao Administrador. |
| Dashboard de Custos              | Gráficos e indicadores — acesso exclusivo para Administrador.                   |

## 5. Perfis de Usuário

| Perfil        | Permissões                                                                       |
| ------------- | -------------------------------------------------------------------------------- |
| Administrador | Acesso total a relatórios, dashboards e edição de custos.                        |
| Gerente       | Visualiza apenas a seção *Atividades e Horas*; não tem acesso à seção de custos. |
| Desenvolvedor | Visualiza apenas a seção *Atividades e Horas*; não tem acesso à seção de custos. |

## 6. Roadmap

* Integração completa com a API do Jira
* Relatórios de Atividade, Produtividade e Comparação
* Gerenciamento de Valor/Hora do Desenvolvedor
* Dashboard de Saúde do Projeto (Custos, Issues e Bugs)
* Módulo de Cadastro e Perfis Avançados