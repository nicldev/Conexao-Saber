# Plataforma IntegraEdu – Conjunto Ceará

## Problema & Justificativa
Estudantes da rede pública do Conjunto Ceará enfrentam barreiras de acesso a cursinhos comunitários (informação dispersa, vagas ociosas, pouca visibilidade, logística e comunicação).  
A plataforma busca otimizar o uso das vagas e conectar escolas, cursinhos e alunos.

## Objetivos
- Conectar estudantes, escolas e cursinhos comunitários.
- Garantir maior ocupação das vagas disponíveis.
- Apoiar desempenho rumo ao ENEM/vestibulares.
- Promover inclusão educacional alinhada ao ODS 11.

## Escopo
**MVP:**
- Web (instituições): cadastro, gestão de turmas/vagas.  
- Mobile (estudantes): cadastro, busca, inscrição e notificações.  
- API REST integrando Web e Mobile.  

**Extensões futuras:**
- Recomendação personalizada, trilhas de estudo, relatórios, bolsas e chat.

## Alinhamento ao ODS 11
O projeto fortalece redes comunitárias, melhora o uso de infraestrutura local e amplia o acesso à educação, tornando cidades mais inclusivas e sustentáveis.

## Arquitetura (visão geral)
- **Frontend Web (instituições):** React/Next, Tailwind.  
- **Mobile (estudantes):** Kotlin (Jetpack Compose) ou Flutter.  
- **Backend/API:** RESTful (NestJS/Ktor/Spring Boot), JWT/Auth.  
- **Banco de Dados:** PostgreSQL.  
- **Infra:** Docker, CI/CD, hospedagem em nuvem.  

### Diagrama da Arquitetura
(Adicionar imagem em docs/architecture/architecture.png)

## Tecnologias propostas
React, Kotlin/Flutter, Node.js/Kotlin, PostgreSQL, Docker, CI/CD, Swagger/OpenAPI, Figma.

## Cronograma (Etapa 2 – N708)
| Semana | Entregas |
|--------|-----------|
| 1 | Setup repositório, CI/CD, backend scaffold, DB |
| 2 | Autenticação (login/registro), RBAC |
| 3 | CRUD de Organizações/Escolas |
| 4 | CRUD de Turmas + listagem pública |
| 5 | Inscrições + notificações |
| 6 | App Mobile (login, listagem, inscrição) |
| 7 | Relatórios + auditoria |
| 8 | Acessibilidade, testes E2E, release candidate |

## Equipe
- Nome 1 – PO/Analista  
- Nome 2 – Arquiteto(a)  
- Nome 3 – Dev Web  
- Nome 4 – Dev Mobile  
- Nome 5 – Dev Backend  
- Nome 6 – UX/UI  
- Nome 7 – QA  
