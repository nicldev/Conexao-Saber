# Especificação de APIs

## Autenticação
- POST /auth/register  
- POST /auth/login  
- POST /auth/refresh  

## Instituições
- POST /orgs, GET /orgs  
- POST /schools, GET /schools  

## Turmas
- POST /classes (org)  
- GET /classes (público, com filtros)  
- GET /classes/:id  
- PATCH /classes/:id  
- DELETE /classes/:id  

## Inscrições
- POST /classes/:id/enroll (student)  
- GET /me/enrollments (student)  
- PATCH /enrollments/:id/cancel  

## Relatórios
- GET /reports/capacity  

## Segurança
- JWT, RBAC, refresh tokens.  
- Hash de senha, LGPD compliance.  
