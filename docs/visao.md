# Documento de Visão

## 1. Objetivo

Automatizar o sistema para proporcionar um atendimento mais célere, organizado e facilitado, gerando autonomia para marcação de consultas e visualização de resultados.

## 2. Escopo

- Cadastro de usuários
- Disponibilidade de cada médico
- Cadastro de pacientes
- Agendar/cancelar consultas
- Exibir mensagens de erro claras em caso de conflito de horários

## 3. Escopo Fora do Projeto (Out of Scope)

- Agendamento domiciliar
- Envio de mensagens para os médicos
- Faturamento e convênios
- Prontuário eletrônico
- Multi-clínica / multi-unidade
- Relatórios e dashboards avançados

## 4. Regras de Negócio

- **RB-001:** Slots de horário não podem se sobrepor a outros já ocupados.
- **RB-002:** Consultas só podem ocorrer dentro da janela de atendimento do profissional.
- **RB-003:** Cancelamento deve liberar o slot imediatamente.
- **RB-004:** A duração padrão da consulta é de 30 minutos (configurável pelo profissional).

## 5. Premissas

- Horário comercial base: 08h às 18h (ajustável por profissional).
- MVP limitado a uma clínica e até 10 profissionais.

## 6. Stakeholders

- Atendentes
- Médicos
- Pacientes
- Gestor da clínica