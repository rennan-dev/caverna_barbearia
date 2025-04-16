# Requisitos Não Funcionais - Caverna Barbearia

Este documento descreve os requisitos não funcionais do sistema, ou seja, **características de qualidade, desempenho e segurança** que devem ser atendidas.

---

## 🔐 Segurança

- RNF01: As senhas dos usuários devem ser armazenadas com criptografia (ex: bcrypt).
- RNF02: O sistema deverá usar HTTPS para proteger as comunicações.
- RNF03: O acesso às rotas administrativas deverá ser restrito a usuários com permissão de administrador.

---

## 📱 Usabilidade

- RNF04: A interface deverá ser responsiva, adaptando-se a diferentes dispositivos (desktop, tablet e mobile).
- RNF05: A navegação deverá ser intuitiva, com menus claros e fluxo de agendamento simples.

---

## ⚙️ Desempenho

- RNF06: As páginas do sistema deverão carregar em no máximo 2 segundos em redes de velocidade média.
- RNF07: O sistema deverá suportar ao menos 50 usuários simultâneos no MVP.

---

## 🛠️ Manutenibilidade

- RNF08: O código deverá ser modularizado e seguir boas práticas para facilitar manutenção e futuras expansões.
- RNF09: Toda lógica crítica (como agendamento) deverá conter testes automatizados no backend.

---

## 🗃️ Persistência de Dados

- RNF10: Todas as informações de usuários, barbeiros, agendamentos e serviços deverão ser salvas em um banco de dados relacional.

---

## 🕒 Disponibilidade

- RNF11: O sistema deverá estar disponível 24/7, salvo em janelas específicas de manutenção.
