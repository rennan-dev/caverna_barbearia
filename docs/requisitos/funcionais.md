# Requisitos Funcionais - Caverna Barbearia

Este documento descreve os requisitos funcionais do sistema, ou seja, **as funcionalidades que o sistema deverá oferecer** para atender aos objetivos do projeto.

---

## 1. Cliente

1. **Cadastro e Autenticação**

   * O cliente deve poder criar uma conta com e-mail e senha.
   * O cliente deve poder fazer login e logout.
   * O cliente deve poder recuperar senha via e-mail.

2. **Perfil do Cliente**

   * Visualizar e editar dados pessoais (nome, telefone, etc...).
   * Consultar histórico de agendamentos (passados, futuros, cancelados).

3. **Consulta de Serviços e Disponibilidade**

   * Exibir lista de serviços oferecidos (nome, descrição, duração, preço).
   * Mostrar calendário com horários disponíveis de cada barbeiro.

4. **Agendamento de Horário**

   * Selecionar serviço, barbeiro, data e horário disponíveis.
   * Confirmar agendamento e receber número de reserva.

5. **Cancelamento e Remarcação**

   * Cancelar agendamento respeitando prazo mínimo (ex.: até 4h antes).
   * Remarcar agendamento para outra data/hora disponível.

6. **Notificações**

   * Receber e-mail e/ou SMS de confirmação, lembrete e aviso de cancelamento.

7. **Avaliação e Feedback**

   * Após atendimento, avaliar serviço e barbeiro com nota e comentário.

---

## 2. Barbeiro

1. **Dashboard de Atendimentos**

   * Visualizar lista de próximos atendimentos e seu status.
   * Visualizar taxa de ocupação diária e semanal.

2. **Gerenciamento de Serviços**

   * Criar, editar e remover serviços (nome, duração, preço).

3. **Gerenciamento de Agenda Individual**

   * Definir dias e horários de trabalho, folgas individuais e feriados.
   * Bloquear manualmente horários.

4. **Relatórios e Estatísticas**

   * Consultar total de atendimentos por período.
   * Visualizar serviços mais populares e receita gerada.

---

## 3. Administrador

1. **Cadastro de Barbeiros**

   * Adicionar novos barbeiros ao sistema com dados pessoais e foto.

2. **Exclusão de Barbeiros**

   * Remover barbeiros existentes do sistema, mantendo histórico de atendimentos.

3. **Definição de Folgas Coletivas**

   * Definir datas de folga e feriados para todos os barbeiros simultaneamente.
   * Aplicar folgas recorrentes (ex.: todo primeiro sábado do mês) a todos.

4. **Visualização de Relatórios Gerais**

   * Acessar relatórios consolidados de atendimentos e receitas de todo o negócio.