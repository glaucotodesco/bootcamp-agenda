# Sistema de Agendamento de Consultas.

Uma clínica médica necessita controlar a agenda dos médicos, terapeutas, psicólogos, etc.
Todo o sistema de agendamento é feito por telefone somente pelos atendentes da clínica.


# Requisitos:
  - Cada profissinal indica em quais dias da semana e horários ele vai trabalhar, considerando intervalos e hora de almoço.
  - Cada profissional deve indicar o tempo médio de cada uma das suas consultas e sessões (15, 30, 45 e 60).
  - Cada consulta deve durar o tempo indicado por cada profissional, dessa forma, os horários de agendamento são intercalados a cada x minutos.
  - O sistema não deve permitir agendar fora do horário e dias da semana de cada profissional.
  - O sistema não deve permitir agendar duas ou mais pessoas no mesmo dia e horário de um profissional
  - O sistema não deve permitir agendar a mesma pessoa no mesmo dia e horário.
  - O sistema não deve permitir agendar em feriados.
  - O profissinal pode ainda bloquear dias e horários específicos, conforme a sua necessidade e demanada. Por exemplo, bloquear uma data para fazer um treinamento.
  - O atendente pode cancelar ou reagendar uma consulta ou sessão.
  - O sistema deve controlar a frequência de paciente. Ao realizar uma consulta ou sessão, indicar indicar que o paciente veio, caso contrário ele ficará marcado como ausente
  - Ao agendar uma consulta ou sessão, mostrar o histório que ausencias (faltas) do paciente.
  
# Permitir:
  - Cadastrar convênios atendidos pela clínica. 
  - Cadastar pacientes: Nome, telefone, email e observações.
  - Cadastar profissionais, com a sua disponibilidade de atendimento. Nome, especialidade, observações e disponibilidade.
  - Agendar consultas mostrando disponibilidade e faltas do paciente. 
        Ao agendar consultar marcar como particular ou convênio.
        Marcar prioridade: Baixa, Média e Alta
        Enviar SMS e Email um dia antes? (SIM/NÃO)
  - Cancelar consulta
  - Reagendar consultas, mostrando disponibilidade e faltas do paciente.
  - Bloquear datas e horários específicos de um prossifional
  - Listar as consultas do dia a clínica
  - Ao agendar, cancelar ou reagendar uma consulta, guardar o dia, hora e qual atendente fez a operação.
  - Históricos de consultas de um cliente.
  - Listar horários em abertos de um profissional para tentar antecipar consultas por ordem de prioridade.
  - Enviar SMS e email um dia antes da consulta ou sessão.
  - Imprimir relatório das consultas do dia.
  

# Dois perfis:
  - Administrador: Permite criar atendentes
  - Atendente: Permite agendar, cancelar e reagendar consultas.




