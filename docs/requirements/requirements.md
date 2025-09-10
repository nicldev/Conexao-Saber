# Requisitos do Sistema IntegraEdu

## Stakeholders
- Estudantes (usuários finais).  
- Cursinhos comunitários (coordenadores e voluntários).  
- Escolas públicas (orientadores, coordenação pedagógica).  
- Secretarias/ONGs (parceiros, bolsas e apoio).  

## Personas
- **Ana (17):** estudante; busca vaga próxima, trilha ENEM, notificações.  
- **Carlos (28):** coordenador de cursinho; publica turmas, gerencia vagas.  
- **Márcia (42):** orientadora escolar; encaminha alunos e acompanha status.  

## Regras de Negócio
- Instituições verificadas antes de publicar turmas.  
- Vagas limitadas; lista de espera automática.  
- Elegibilidade de bolsas conforme critérios.  
- Idade mínima: 14+.  
- LGPD: consentimento explícito.  

## Requisitos Funcionais (RF)
- RF01. Cadastro/login de estudante.  
- RF02. Cadastro/login de instituição + verificação.  
- RF03. CRUD de turmas.  
- RF04. Busca de turmas com filtros.  
- RF05. Inscrição em turma + lista de espera.  
- RF06. Notificações (push/e-mail).  
- RF07. Acompanhamento escola–estudante.  
- RF08. Relatórios básicos.  
- RF09. Admin: moderação e auditoria.  

## Requisitos Não Funcionais (RNF)
- Segurança: JWT, hash de senhas, TLS.  
- LGPD: consentimento granular, portabilidade.  
- Performance: p95 < 500ms.  
- Disponibilidade ≥ 99,5%.  
- Escalabilidade: 5k MAU.  
- Observabilidade: logs, métricas.  
- Acessibilidade WCAG 2.1 AA.  
- Compatibilidade: Android 8+, navegadores modernos.  
- Usabilidade: inscrição ≤ 3 passos.  
- Manutenibilidade: CI/CD, testes ≥ 70%.  

## Histórias de Usuário
- US01: Estudante quer criar conta e ver turmas adequadas.  
- US02: Estudante quer filtrar turmas por proximidade e horário.  
- US03: Coordenador quer publicar turma e ver inscrições.  
- US04: Orientadora quer acompanhar alunos e relatórios.  
- US05: Admin quer aprovar instituições e auditar alterações.  
