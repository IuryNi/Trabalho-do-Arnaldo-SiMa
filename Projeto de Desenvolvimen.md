# Planejamento de desenvolvimento, SiMa 

## What: 
   Este documento se trata do planejamento para o desenvolvimento do software denominado “SiMa”, que consiste em uma aplicação mobile para o “SIGA” (Sistema integrado de Gestão Acadêmica), responsável pelo gerenciamento das atividades acadêmicas dos alunos das Etecs e Fatecs do estado de São Paulo. 

## Why: 
   Uma versão mobile do já estabelecido SIGA, permite que o acesso à informação seja facilitado, pois possibilita ao aluno o acesso a suas informações em qualquer ambiente por meio do smartphone, outro diferencial e a disponibilidade já que as informações podem ser baixadas no aparelho, que se torna acessível sem a necessidade de internet. Além de fornecer uma experiencia personalizada e idealizada   para o usuário que utilizar o App. 

# Who: 
### Equipe: 
    * PO 
    * Desenvolvedor Pleno 
    * 4 Desenvolvedores Junior 
    * DevOps 
    * QA 

### Responsabilidades: 

#### PO (Product Owner) 
   Responsável por manter a equipe focada no desenvolvimento do SiMa , além de ser o com mais conhecimento do que resultara o produto. 

#### Desenvolvedor Pleno 
   Responsável por apoiar e ajudar os outros desenvolvedores se preciso, revisar e aprovar os commits antes do merge, além de ser o líder da equipe de desenvolvimento.  

#### Desenvolvedores Junior 
   Serão divididos em duas equipes de back e front end, e seguirão o cronograma que será apresentado a seguir. 

#### DevOps 
   Será responsável por construir toda a infraestrutura do sistema e fazer o deploy das versões beta semanalmente. 

#### QA 
   Responsável pela qualidade do produto, e terá a função vital de fazer os testes Gherkin que o repositório do SiMa apresenta. 

## When: 
   Este planejamento visa entregar a versão 1.0 do Software no início do próximo semestre letivo 01/02/2026 (Um de Fevereiro de Dois mil e Vinte seis), e iniciar o desenvolvimento ainda este mês, dia 15/12/2025 (Quinze de dezembro de Dois mil e Vinte cinco), para tanto o desenvolvimento seguira o cronograma abaixo. 

### Cronograma de Desenvolvimento 

| Data de Início | Mile Stone | QA | Deploy | Dificuldade Fibonacci (Referente ao desenvolvimento)| Data Final |
| :--- | :---: | :---: | :---: | :---: | ---: |
| 15/12/2025 | [Tela de Login](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/13) e [Retirar Livro](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/10) | - | - | 33 | 20/12/2025 |
| 22/12/2025 | [Visualizar Notas](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/2) e [Reposição de Aulas](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/6) | Tela de Login e Retirar Livro | - | 27 | 27/12/2025 |
| 29/12/2025 | [Documentação](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/8) e [Rematrícula](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/9) | Visualizar Notas e Reposição de Aulas | Tela de Login e Retirar Livro | 35 | 03/01/2026 |
| 05/01/2026 | "[Trancar](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/7), [Visualizar Faltas](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/3) e [Horários](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/4)" | Calendário e Rematrícula | Visualizar Notas e Reposição de Aulas | 29 | 10/01/2026 |
| 12/01/2026 | [Calendário](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/5) e [Devolver Livros](https://github.com/IuryNi/Trabalho-do-Arnaldo-SiMa/milestone/11) | "Trancar, Visualizar Faltas e Horários" | Calendário e Rematrícula | 20 | 17/01/2026 |
| 19/01/2026 | Resolver Bugs | Calendário e Devolver Livros | "Trancar, Visualizar Faltas e Horários" | - | 24/01/2026 |
| 26/01/2026 | Resolver Bugs | Revisão p/ lançamento | Calendário e Devolver Livros | - | 31/01/2026 |

[Timeline do Cronograma](https://github.com/users/IuryNi/projects/6/views/6?sortedBy%5Bdirection%5D=asc&sortedBy%5BcolumnId%5D=222411276)

Ao final deste cronograma o programa terá todas as funcionalidades requisitadas no repositório do GitHub, e será lançado para o público, porém manutenções terão de ser feitas com o feedback dos usuários. 

## Where: 
   Todo o desenvolvimento será realizado em regime home-office, com reuniões diárias via Google Meet e organização centralizada no GitHub. O DevOps utilizará ambientes cloud para deploy e pipelines de CI/CD. As ferramentas de design serão colaborativas, como o Figma. 

## How  
   O desenvolvimento do SiMa será realizado seguindo práticas ágeis, utilizando o framework Scrum em ciclos semanais de entrega (sprints). A equipe atuará de forma colaborativa, seguindo um fluxo claro de desenvolvimento, versionamento, testes e deploy contínuo. 

### Metodologia de Desenvolvimento  
O projeto utilizará Scrum, com:
1. Daily meetings (reuniões rápidas diárias) para alinhamento.
2. Sprints semanais, conforme o cronograma apresentado.
3. Revisões de sprint para apresentação do que foi desenvolvido.
4. Retrospectivas para ajustes no processo.
5. As tarefas serão organizadas no GitHub Projects, permitindo visualização de progresso. Serão definidos critérios de aceitação claros para cada tarefa, e métricas de qualidade do código serão monitoradas, incluindo cobertura mínima de testes e aprovação obrigatória em code review.  

Métricas e KPIs de sprint:  
* Velocity: quantidade de tarefas concluídas por sprint.  
* Taxa de conclusão: tarefas concluídas vs planejadas.  
* Tempo médio de resolução de bugs.  
* Indicadores de performance do sistema (resposta do backend, uso de memória, crashes do app).   

### Processo de Desenvolvimento  
As tarefas serão divididas entre frontend (React Native/TypeScript) e backend (Node.js + Express).  
O fluxo de trabalho seguirá as seguintes etapas:  
1. Planejamento da tarefa (PO + Dev Pleno)  
2. Criação da branch no Git seguindo o padrão:  
_feature/nome-da-funcionalidade_ 
3. Desenvolvimento da funcionalidade  
4. Commit e versionamento semântico  
5. Pull Request para revisão do Dev Pleno  
6. Code Review obrigatório pelos desenvolvedores  
7. Testes automatizados:  
    * Unitários com Jest  
    * Integração com Supertest  
    * Validação do QA, incluindo testes Gherkin  
8. Merge para branch principal após aprovação  
9. Deploy automático realizado pelo DevOps  

### Infraestrutura e Deploy  
#### O DevOps criará pipelines de integração contínua utilizando GitHub Actions:  
* Build do backend  
* Build do app mobile (versão beta)  
* Execução automática dos testes  

#### O deploy será realizado semanalmente:  
* Backend hospedado em ambiente cloud (AWS ou Render)  
* Banco PostgreSQL configurado no mesmo provedor  
* Aplicativo mobile distribuído em APK para testes internos  

#### Além disso, serão implementados:  
* Monitoramento de performance e logs centralizados  
* Alertas para falhas críticas  
* Estratégias de backup e recuperação do banco de dados  

#### Versionamento do app mobile:  
* Cada release terá versão semântica (ex.: 1.0.0)  
* Builds beta distribuídos internamente para testes antes do release oficial  
* Histórico de versões mantido no repositório  

### Segurança e Autenticação  
1. Implementação de JWT para autenticação  
2. Armazenamento seguro de senhas utilizando hashing (bcrypt)  
3. Ações de proteção adicionais:  
* Validação de tokens em todas as rotas privadas  
* Sanitização de dados para evitar SQL Injection  
* Uso de HTTPS/SSL no servidor  
* Procedimentos de backup e recuperação do banco de dados  

### Design e Experiência do Usuário  
* As telas serão prototipadas no Figma antes do desenvolvimento  
* O frontend usará Tailwind RN para estilização ágil e padronizada  
* Componentes serão construídos de forma modular, reutilizável e responsiva
* Além disso, a equipe acompanhará métricas de experiência do usuário (UX) e fará ajustes contínuos com base em feedback interno e testes beta.  

### Documentação  
1. A documentação da API será feita em Swagger
2. Procedimentos internos, definições de tarefas e orientações técnicas serão mantidos em Markdown dentro do repositório  
3. Instruções de setup, build e contribuições estarão no README principal  
4. Serão mantidos registros de decisões técnicas (decision logs) e documentação de processos para referência futura.  

### Manutenção Pós-Lançamento  
#### Após a versão 1.0, será estabelecido um ciclo contínuo de:  
* Correção de bugs detectados pelos usuários  
* Refinamentos de UX  
* Implementação de novas funcionalidades conforme prioridade do PO  
* O monitoramento contínuo do sistema permitirá identificação rápida de problemas, e métricas de uso do aplicativo serão acompanhadas para priorização de melhorias.  

#### KPIs de manutenção pós-lançamento:  
* Tempo médio de resolução de incidentes  
* Frequência de crashes ou falhas críticas 
* Métricas de engajamento e adoção do app  

## How much 

O desenvolvimento do aplicativo mobile SiMa, destinado à comunidade acadêmica do Centro Paula Souza, envolve custos estimados relacionados à alocação da equipe, ferramentas utilizadas, infraestrutura, publicação e manutenção pós-lançamento. Como se trata de um órgão público, parte desses custos, como domínio e infraestrutura, é absorvida pelas verbas governamentais 

### Custos da Equipe: 

| Profissional | Quantidade | Regime | Total mensal (R$) |
| :----------: | :--------: | :----: | :---------------: |
| Product Owner | 1 | Full time | 7.500 |
| Dev Pleno | 1 | Full time | 10.000 | 
| Dev Junior | 4 | Full time | 4.000 |
| DevOps | 1 | Meio período | 4.500 |
| QA | 1 | Full time | 6.000 |

Subtotal equipe: R$ 88.000,00 

### Custos com ferramentas de design, documentação e gerenciamento: 

| Ferramenta | Custo (R$) | Observação |
| :--------: | :--------: | :--------: |
| Figma | 00.0 | Plano gratuito atende |
| Git/Github | 00.0 |Totalmente gratuito |
| VSCode | 00.0 |Open Source |
| Swagger | 00.0 | Open Source |

Subtotal ferramentas: R$ 0,00 

### Referência de mercado para infraestrutura técnica: 

O backend do SiMa, o banco de dados e os pipelines de integração contínua já são fornecidos pelo Centro Paula Souza. Para fins de planejamento orçamentário e referência técnica, apresentamos uma estimativa de mercado: 

| Recurso Técnico | Estimativa Mensal em Reais (R$) | Observação |
| :--------: | :--------: | :--------: |
| Servidor Backend e API | 100 a 300 | Hospedagem do backend do aplicativo |
| Banco de Dados PostgreSQL | 40 a 80 | Armazenamento das informações acadêmicas |
| Logs e Monitoramento | 20 a 40 | Supervisão e manutenção do sistema |
| Certificado SSL | 0 | Incluído na infraestrutura fornecida pelo Centro Paula Souza |
| Pipelines de Integração Contínua (GitHub Actions) | 0 | Plano gratuito da plataforma |

Obs.: Este custo é apenas referência de mercado. Na prática, o Centro Paula Souza disponibiliza toda a infraestrutura, eliminando gasto direto com servidores e banco de dados. 

### Custo estimado do projeto: 
* Custos da equipe: R$ 88.000 
* Infraestrutura técnica: R$ 0 (fornecida pelo governo) 
* Publicação do aplicativo: R$ 0 
* Operacional: 0 a 1.200 (coberto pelo governo) 
* Reserva para imprevistos (15%): R$ 13.200 

A reserva de 15% é baseada em recomendações de gestão de projetos (PMBOK, boas práticas de TI) e serve para cobrir riscos previsíveis, garantindo que o projeto seja entregue dentro do prazo e com qualidade, mesmo diante de ajustes inesperados. 

Total estimado: aproximadamente R$ 101.200 a R$ 102.400 

_Os valores apresentados acima representam o custo do desenvolvimento caso fossem necessários recursos externos, em um projeto privado. Como se trata de um projeto público, a maior parte da infraestrutura, domínio institucional e operação já é fornecida pelo Centro Paula Souza, reduzindo significativamente o gasto direto._
