# Requisitos Funcionais - Caverna Barbearia

Este documento descreve os requisitos funcionais do sistema, ou seja, **as funcionalidades que o sistema deverá oferecer** para atender aos objetivos do projeto.

---

## 👤 Usuário Comum

- RF01: O usuário deverá poder criar uma conta no sistema.
- RF02: O usuário deverá poder fazer login com e-mail e senha.
- RF03: O usuário deverá visualizar a lista de barbeiros disponíveis.
- RF04: O usuário deverá visualizar os serviços oferecidos por cada barbeiro e o valor.
- RF05: O usuário deverá poder agendar um horário com um barbeiro, escolhendo data, horário, serviço e o valor total.
- RF06: O usuário deverá poder visualizar seus agendamentos futuros.
- RF07: O usuário deverá poder cancelar ou reagendar um agendamento (antes do horário marcado).
- RF08: O usuário deverá poder editar suas informações pessoais (nome, telefone, etc).

---

## 🛠️ Administrador

- RF09: O administrador deverá poder fazer login com credenciais especiais.
- RF10: O administrador deverá poder cadastrar, editar e excluir barbeiros.
- RF11: O administrador deverá poder cadastrar, editar e excluir serviços (corte, barba, combo etc).
- RF12: O administrador deverá poder associar serviços específicos a cada barbeiro.
- RF13: O administrador deverá visualizar todos os agendamentos realizados, com filtros por barbeiro, data e usuário.
- RF14: O administrador poderá bloquear horários específicos na agenda de um barbeiro.

---

## 🛡️ Funcionalidades Gerais

- RF15: O sistema deverá evitar conflitos de horários (não permitir dois agendamentos para o mesmo barbeiro no mesmo horário).
- RF16: O sistema deverá validar todos os campos obrigatórios nos formulários.
- RF17: O sistema deverá garantir que apenas usuários autenticados acessem áreas restritas.
