# SiMa Mobile
O Sima é um app mobile de gestão academico, com uma interface que permite aos usuários acessarem dados relevantes de forma rápida e eficiente.

# Stacks Utilizadas

![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

- **Frontend (Mobile):** React Native + TypeScript  
- **Backend (API):** Node.js + Express + TypeScript 
- **Banco de Dados:** PostgreSQL  
- **Gerenciamento de Pacotes:** npm  
- **Controle de Versão:** Git e GitHub  
- **Ferramentas de Design:** Figma  
- **Testes:** Jest  
- **Documentação:** Markdown e Swagger

# Navegação Rápida
* [ Histórias de Usuario ](#Histórias-de-Usuario)
* [ Diagramas de Caso de Uso ](#Diagramas-de-Caso-de-Uso)
* [ Diagramas de Sequencia ](#Diagramas-de-Sequencia)
* [ Wireframe ](#Diagrama_visual)
* [ Protótipo ](#Protótipo)
* [ Orientações Gerais ](#Orientações-Gerais)
* [ Autores ](#Autores)

# Histórias de Usuário 

## Requisitos Funcionais

Informações do curso:
* Como aluno, quero acessar meus horários de aula para organizar melhor minha rotina.
* Como aluno, quero visualizar minhas faltas para controlar minha frequência a evitar reprovação.


Solicitações acadêmicas:
* Como aluno, quero solicitar o trancamento do curso pelo app caso eu precise interromper
temporariamente meus estudos.
* Como aluno, quero solicitar declarações de matrícula para apresentar em estágios, empregos ou instituições externas.
* Como aluno, quero realizar minha rematrícula online para evitar filas e burocracia presencial.
  
  
Calendário escolar:
* Como aluno, quero visualizar o calendário anual acadêmico para acompanhar datas de provas, feriados e eventos.
* Como aluno, quero visualizar reposições de aula para me adaptar caso haja mudanças no cronograma.


Biblioteca:
* Como aluno, quero lretirar livros da biblioteca diretamente pelo app para facilitar meu acesso o material.
* Como aluno, quero retornar livros da biblioteca de forma registrada para manter meu histórico organizado.
* Como aluno, quero doar livros para a biblioteca para ajudar a comunidade acadêmica.

* Representação visual:[historias_de_usuario.pdf](https://github.com/user-attachments/files/22384241/historias_de_usuario.1.pdf)

## Requisitos Não Funcionais

* Segurança: O programa precisa ter um banco de dados criptografados e Tokens de acesso temporarios, pois possui dados sensíveis.(realizar pen-teste)
* Manutibilidade: Em caso de necessidade de manutenção o programa necessita ser facil de manusear.(usar padrões do GOF(Gang of Four) ter documentação e bem comentado)
* Usabilidade: O programa tem der ser intuitivo para os usuarios.(realizar Teste de usabilidade)
* Desempenho: Definir tempos meta de execução para as aplicações com determinada quantidade de usúarios.(usando o jmeter)
* Confiabilidade: O programa precisa estar em funcionamento constantemente para acesso dos alunos.
* Portabilidade: Como existem diversos dispositivos móveis no mercado, a necessidade de portabilidade é imprescindível.
* Escalabilidade: Nas ultimas semanas de rematricula ou matricula, o sistema deve suportar o volume simultâneo de usuários.

# Diagrama de Caso de Uso

* Caso de Uso: Alunos
<img width="538" height="654" alt="Captura de tela 2025-09-17 092354" src="https://github.com/user-attachments/assets/4cf1bb3c-9da8-48b5-8dc0-5c994d81e452" />

# Diagrama de Sequência

<img width="1095" height="674" alt="Captura de tela 2025-09-17 084134" src="https://github.com/user-attachments/assets/a6f8cc76-439f-4295-ae70-a0f54df86312" />
[Diagrama](https://github.com/user-attachments/files/22384662/diagramaSequencia.2.pdf)

# BackLog
[BackLog](https://github.com/users/IuryNi/projects/6)

# Wireframe
Representação visual simplificada
[WireFrame](https://www.figma.com/proto/hyUspCnZ7IQWMP0nR52Tst/Dravter-Lo-fi-Wireframe-Kit--Community-?node-id=5905-634&p=f&t=TA63gO2EmN0ybfLE-1&scaling=min-zoom&content-scaling=fixed&page-id=709%3A14319&starting-point-node-id=5905%3A634)

# Protótipo
Protótipo provisório do app 
[Protótipo](https://www.figma.com/proto/6B38xuZSYpVvjsyD8SWhpP/SiMA---Prot%C3%B3tipo?node-id=0-1&t=QEinYtB4Gsj76kTo-1)

<details>
<summary><h1>Orientações Gerais</h1></summary>

### 🧭 Antes de iniciar o desenvolvimento

---

#### 🔹 Clonar o repositório
```bash
git clone git@github.com:IuryNi/Trabalho-do-Arnaldo-SiMa.git
```

#### 🔹 Acessar a pasta do projeto
```bash
cd Trabalho-do-Arnaldo-SiMa
```

#### 🔹 Instalar as dependências
```bash
npm install
```

---

### 🌱 Criar uma nova branch a partir da branch principal (`main`)

#### Verifique a branch atual:
```bash
git branch
```

#### Caso não esteja na branch `main`, altere para ela:
```bash
git checkout main
```

#### Crie uma nova branch para a funcionalidade ou ajuste que será desenvolvido  
Recomenda-se seguir o padrão **Conventional Commits** para nomear branches, por exemplo:
```
feat/CreateHeader
feat/CreateEndPointToFaltas
fix/AdjustLoginValidation
```

**Exemplo:**
```bash
git checkout -b feat/CreateHeader
```

---

### 💾 Adicionar as alterações ao controle de versão

#### Verifique os arquivos modificados:
```bash
git status
```

#### Adicione as alterações ao stage:
```bash
git add .
```

#### Confirme novamente:
```bash
git status
```

#### Realize o commit utilizando o padrão **Conventional Commits**:
```bash
git commit -m "feat: create header component"
```

---

### ☁️ Enviar a branch para o repositório remoto
```bash
git push -u origin feat/CreateHeader
```

---

### 📌 Criar o Pull Request (PR)

1. Acesse a aba **Pull Requests** no GitHub.  
2. Clique em **New Pull Request**.  
3. Em **Compare**, selecione cuidadosamente a sua branch.  
4. Defina um título claro e descritivo, seguindo o padrão:
   ```
   feat: create header component
   ```
   ou
   ```
   feat: implement endpoint to manage student absences
   ```
5. Adicione uma breve descrição sobre o que foi desenvolvido.  
6. Clique em **Create Pull Request** e confirme.  
7. Verifique se o PR foi criado corretamente.

---

</details>

# Autores
* Gabriella Scattolin
* Iago Rodrigues
* Iury Nicolau
* Lucas Viana


