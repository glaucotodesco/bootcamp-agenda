# Sistema de Agendamento de Consultas.

Uma clínica médica necessita controlar a agenda dos médicos, terapeutas, psicólogos, etc.
Todo o sistema de agendamento é feito por telefone somente pelos atendentes da clínica.



# Requisitos:
  - Cada profissinal indica em quais dias da semana e horários ele vai trabalhar em intervalos de 30 minutos.
  - Um profissional pode estar ativo ou desativo. 
  - Cada consulta deve durar o tempo de 30 minutos e os horários de agendamento são intercalados a cada 30 minutos.
  - O sistema não deve permitir agendar fora do horário e dias da semana de cada profissional.
  - O sistema não deve permitir agendar duas ou mais pessoas no mesmo dia e horário de um profissional
  - O sistema não deve permitir agendar a mesma pessoa no mesmo dia e horário.
  - O sistema não deve permitir agendar em feriados.
  - O profissinal pode ainda bloquear dias e horários específicos, conforme a sua necessidade e demanada. Por exemplo, bloquear uma data para fazer um treinamento ou bloquear um horário (manhã ou tarde por exemplo)
  - O atendente pode cancelar uma consulta ou sessão.
  - O sistema deve controlar a frequência de paciente. Ao realizar uma consulta ou sessão, indicar indicar que o paciente veio, caso contrário ele ficará marcado como ausente
  - Ao agendar uma consulta, selecionar primeiro a área e depois o profissional
  - Ao agendar uma consulta, apresentar o primeiro dia e horário disponível do profissional selecionado.
  - Agendar somente com profissionais ativos.
  - Não agendar no passado.
  - Não remover clientes com consultas ou sessões.
  - Não remover profissionais com consultas ou sessões.
  - Não remover Area e Tipo de Consulta com relacionamentos.

  
# Permitir:
  - Cadastrar o tipo de atendimento: particular, convenio1, convênio 2
  - Cadastar pacientes: Nome, telefone, email, data de nascimento, género e observações.
  - Cadastar profissionais, com a sua disponibilidade de atendimento. Nome, especialidade, observações e disponibilidade. Ao cadastrar um profissional ele já fica ativado.
  - No cadastro do profissional ter a opção de ativar e desativar
  - Agendar consultas mostrando disponibilidade e faltas do paciente. 
        Ao agendar consultar marcar como particular ou convênio.
  - Cancelar consulta - Marcar o motivo nos comentários.
  - Bloquear datas e horários específicos de um prossifional
  - Listar as consultas do dia a clínica com opção de imprimir
  - Históricos de consultas de um cliente.
  
  

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


