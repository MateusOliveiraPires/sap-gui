Laboratório SAP Basis – Administração de Ambiente SAP NetWeaver ABAP
Visão Geral

Implantação e administração de ambiente SAP NetWeaver ABAP em servidor Linux (SUSE Linux Enterprise Server), contemplando atividades de inicialização de serviços, conectividade SAP GUI, monitoramento operacional, gerenciamento de autorizações e acompanhamento de banco de dados.

Administração da Camada de Infraestrutura
Inicialização dos Serviços SAP

Realização do start-up e shutdown controlado do ambiente SAP utilizando ferramentas administrativas do sistema operacional Linux.

Atividades executadas:

Inicialização do SAP Start Service (sapstartsrv) através do comando startsap.
Verificação dos processos críticos da instância:
Dispatcher
Message Server
Work Processes DIA (Dialog)
BTC (Background)
SPO (Spool)
UPD (Update)
Monitoramento do status operacional dos serviços SAP no ambiente Linux.
Validação da disponibilidade da instância para acesso dos usuários.
Configuração de Conectividade SAP GUI
Cadastro de Conexões

Configuração e manutenção de acessos utilizando SAP GUI Logon.

Parâmetros configurados:

Tipo de conexão: Custom Application Server
Application Server: Hostname/IP do servidor SAP
Instance Number: 00
System ID (SID): NSP
Definição de clientes (Mandantes) para acesso administrativo e funcional.
Autenticação e Acesso

Execução de testes de conectividade e autenticação utilizando usuários administrativos e desenvolvedores.

Recursos utilizados:

SAP GUI for Windows
SAP Easy Access
Administração de clientes (000, 001 e 100)
Monitoramento Operacional e Administração Basis
SM21 – System Log

Monitoramento de eventos críticos do sistema SAP.

Atividades realizadas:

Análise de logs do sistema.
Identificação de falhas de comunicação.
Verificação de erros de banco de dados.
Auditoria de eventos gerados por usuários e Work Processes.
Investigação de mensagens de erro e problemas de runtime.
SM37 – Job Monitoring

Acompanhamento de processos executados em background.

Atividades realizadas:

Monitoramento de Jobs agendados.
Análise de Jobs em execução.
Investigação de Jobs cancelados.
Validação de execuções periódicas e integrações.
PFCG – Administração de Perfis e Autorizações

Gerenciamento de segurança e controle de acesso.

Atividades realizadas:

Criação e manutenção de Roles.
Atribuição de perfis de autorização.
User Comparison.
Aplicação do princípio de menor privilégio.
Controle de acesso por transação e objeto de autorização.
DBACOCKPIT – Administração de Banco de Dados

Monitoramento da saúde e performance do banco de dados SAP.

Atividades realizadas:

Acompanhamento do crescimento de tablespaces.
Monitoramento de utilização de memória.
Análise de performance SQL.
Identificação de gargalos e locks.
Verificação de rotinas de backup e recuperação.
Competências Desenvolvidas
SAP Basis Administration
SAP NetWeaver ABAP
SAP GUI
Linux (SUSE Linux Enterprise Server)
Administração de Usuários SAP
Gerenciamento de Autorizações (PFCG)
Monitoramento de Jobs (SM37)
Análise de Logs (SM21)
Administração de Banco de Dados (DBACOCKPIT)
Troubleshooting SAP
Monitoramento de Processos SAP
Segurança e Governança de Acessos
Transporte de Objetos SAP
Administração de Ambientes SAP
Resultado do Laboratório

Implementação bem-sucedida de um ambiente SAP NetWeaver ABAP funcional, permitindo a execução das principais atividades operacionais de um Analista SAP Basis, incluindo administração da infraestrutura, gerenciamento de acessos, monitoramento de processos, análise de desempenho e suporte operacional ao ambiente SAP.
