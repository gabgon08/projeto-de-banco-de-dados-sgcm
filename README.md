SISTEMA DE GERENCIAMENTO DE CONSULTÓRIO MÉDICO
O sistema visa registrar e organizar informações essenciais sobre pacientes, médicos, agendamentos de consultas, registros médicos e controle de pagamentos.
OBJETIVO
O objetivo deste projeto é construir um banco de dados relacional que permita o gerenciamento eficiente dos processos de um consultório médico. Através deste sistema, é possível:
•	Agendar e registrar consultas.
•	Armazenar informações de pacientes e médicos.
•	Manter o histórico de atendimentos e diagnósticos dos pacientes.
•	Gerenciar pagamentos e status de faturamento das consultas.
SOFTWARE UTILIZADO
•	Sistema de Gerenciamento de Banco de Dados (SGBD): MySQL
o	Linguagem de Modelagem: SQL
ESTRUTURA DO PROJETO
FUNÇÕES DAS TABELAS:
•	PACIENTES: Armazena os dados dos pacientes, incluindo informações pessoais e de contato.
•	MEDICOS: Guarda as informações dos médicos, como nome, especialidade e CRM.
•	SETORES: Lista os setores da clínica/hospital onde os atendimentos acontecem.
•	PROCEDIMENTOS: Define os tipos de procedimentos médicos realizados.
•	CONSULTAS: Registra os agendamentos, associando paciente, médico, setor e outros detalhes.
•	REGISTROSMEDICOS: Guarda o histórico médico do paciente, com seus diagnósticos e suas prescrições.
•	PAGAMENTOS: Responsável pelo controle financeiro das consultas, com dados sobre valor, método e status de pagamento.
