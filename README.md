# Sistema de Agendamento de Consultas.

Uma clínica médica necessita controlar a agenda dos médicos, terapeutas, psicólogos, etc.
Todo o sistema de agendamento é feito por telefone somente pelos atendentes da clínica.
Essa primeira versão será um MVP (Produto mínimo viável), dessa forma, atender somente as necessidades do MVP (não invertar novos requisitos).
Existem diversas outras funcionalidades que serão implementadas em versões futuras, assim que o MVP for validado pelo cliente.


# Requisitos da primeira versão (MVP):
  - Cada profissinal indica em quais dias da semana e horários ele vai trabalhar em intervalos de 30 minutos das 08:00 às 12:00 e das 13:00 às 18:00 horas de segunda à sexta). 
  - Um profissional pode estar ativo ou desativo. 
  - Cada consulta deve durar o tempo de 30 minutos e os horários de agendamento são intercalados a cada 30 minutos (das 08:00 às 12:00 e das 13:00 às 18:00 horas de segunda à sexta)
  - O sistema não deve permitir agendar fora do horário e dias da semana de cada profissional.
  - O sistema não deve permitir agendar duas ou mais pessoas no mesmo dia e horário de um profissional
  - O sistema não deve permitir agendar a mesma pessoa no mesmo dia e horário.
  - O atendente pode cancelar uma consulta ou sessão quando solicitado pelo cliente.
  - O sistema deve controlar a frequência de paciente (Presente ou Ausente)
  - Ao agendar uma consulta, selecionar primeiro a área e depois o profissional
  - Ao agendar uma consulta, apresentar o primeiro dia e horário disponível do profissional selecionado.
  - Agendar somente com profissionais ativos.
  - Não agendar no passado.
  - Não remover clientes com consultas ou sessões realizadas.
  - Não remover profissionais com consultas ou sessões realizadas.
  - Não remover Area e Tipo de Consulta com relacionamentos.
  

  
# Observações:
  - Cadastrar o tipo de atendimento: particular, convenio1, convênio 2
  - Cadastar pacientes: Nome, telefone, email, data de nascimento, género e observações.
  - Cadastar profissionais, com a sua disponibilidade de atendimento. Nome, especialidade, observações e disponibilidade. Ao cadastrar um profissional ele já fica ativado.
  - No cadastro do profissional ter a opção de ativar e desativar o mesmo (não excluir profissinais, apenas desativar). Ao desativar um profissional, as consultas em aberto continuam valendo, apenas novos agendamentos não serão permitidos.
  - Ao agendar uma consulta, confirmar o telefone do cliente selecionado.
  - Cancelar consultas profissionais - Marcar o motivo nos comentários. Ao cancelar uma consulta a mesma deve continuar no histórico do     cliente.    Somente a data e horário deve ser liberados para novos agendamentos.
  - Listar as consultas do dia da clínica, selecionando a área e o profissional. Essa opção deve permitir definir o cliente como ausente ou presente.
  - Listar os históricos de consultas de um cliente.

  
  

# Dois perfis:
   - Operador: 
    * Permite criar Clientes
    * Permite agendarm, cancelar e reagendar consultas.

   - Administrador: 
    * Faz tudo que o operador
    * Permite criar operadores
    * Permite criar Tipo de Agendamento
    * Permite criar Areas
    * Permite criar profissionais Profissionais
    * Permite Ativar e Desativar Profissionais
    
# Responsividade
  - Ter o layout correto para larguras de tela com 350px ou mais.
  - Não considerar larguras menores que 350px


