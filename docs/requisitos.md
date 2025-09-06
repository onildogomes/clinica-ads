#Requisitos Funcionais para o sistema de Clínica
RU1 - Quero cadastrar os médicos
RF1 - O sistema deve possibilitar o cadastro de médicos com os seguintes dados: nome completo, crm, especialidade, disponibilidade, cpf
RU2 - Quero cadastrar os pacientes
RF2 - O sistema deve possiblitar o cadastro de pacientes com os seguintes ddos: nome completo, data nascimento, sexo, cpf, se possui plano
RU3 - Quero agendar consultas
RF3 - O sistema deve permitir o agendamento de consultas com data, hora, profissional e tipo de serviço
RU4 - Quero acessar o histórico de atendimentos
RF4 - O sistema permitir que o médico registre e consulte prontuários eletrônicos
RU5 - O médico quer registrar prescrições eletrônicas com facilidade
RF5 - O sistema deve gerar receitas médicas eletrônicas em PDF com assinatura digital
RU6 - O administrador quer ver relatórios financeiros
RF6 - O sistema deve gerar relatórios financeiros mensais baseados nos atendimentos e pagamentos realizados
RU7 - O paciente quer receber lembretes de consultas
RF7 - O sistema deve enviar lembretes automáticos de consulta por e-mail e SMS
RU8 - O gestor deseja controlar o estoque de materiais
RF8 - O sistema deve controlar o estoque de materiais e alertar quando estiver abaixo do nível mínimo
RU9 - O sistema deve registrar pagamentos e formas deles
RF9 - O sistema deve permitir o registro de pagamentos com diferentes formas: dinheiro, cartão, convênio, etc
RU10 - O gestor quer controlar permissões de usuários
RF10 - O sistema deve permitir o cadastro de usuários com perfis e permissões diferentes (recepcionista, médico etc)

#Requisitos Não Funcionais:
RNF1 - O sistema deve responder às ações do usuário em até 2 segundos para garantir agilidade no atendimento
RNF2 - O sistema deve estar disponível pelo menos 99,5% do tempo, com no máximo 2 horas de indisponibilidade por mês
RNF3 - O sistema deve exigir autenticação por usuário e senha, com controle de permissões para acesso a dados sensíveis
RNF4 - O sistema deve ser compatível com os principais navegadores (Chrome, Firefox, Edge) e dispositivos móveis
RNF5 - O sistema deve realizar backups automáticos diários e permitir recuperação rápida dos dados em caso de falhas

#Requisitos de Software
RS1 - O software deve permitir cadastro, edição, exclusão e consulta de pacientes, médicos, agendamentos e atendimentos
RS2 - Deve permitir envio automático de notificações (SMS, e-mail) para pacientes sobre consultas e exames
RS3 - A interface deve ser responsiva, acessível e compatível com diferentes dispositivos (desktop, tablets, celulares)
RS4 - Deve ser compatível com os sistemas operacionais mais usados (Windows, Linux) e navegadores modernos
RS5 - Deve realizar backups periódicos automáticos e permitir recuperação rápida dos dados em caso de falhas
