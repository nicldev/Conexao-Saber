# Modelo de Dados

## Entidades e Relacionamentos
- Usuário (Student, Org, School, Admin).  
- Organização (cursinho/ONG).  
- Escola.  
- Turma.  
- Inscrição.  
- Vínculo Escola–Estudante.  
- Auditoria de Logs.  

## Diagrama ER
(Adicionar imagem em docs/database/database_model.png)

## Dicionário de Dados
- USER.role: enum {student, org, school, admin}.  
- ENROLLMENT.status: enum {confirmada, lista_espera, cancelada, concluida}.  
- CLASS.totalSeats / takenSeats: regra: não exceder limite.  
- ORG.verified: apenas admin pode alterar.  
