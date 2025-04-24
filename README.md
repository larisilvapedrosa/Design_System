# 🏥 # Documentação do Projeto: Clínica Médica

## 🏗️ Arquitetura

### Estilo Arquitetural
Adotamos o estilo Microsserviços, promovendo escalabilidade, resiliência e implantação independente dos módulos do sistema.

### Padrão Arquitetural
O padrão arquitetural adotado será o **MVC (Model-View-Controller)**, visando uma separação clara entre regras de negócio, lógica de apresentação e manipulação de dados. Isso facilita a evolução do sistema e promove um desenvolvimento mais organizado.

## 🎨 Design System

### 🧩 Identidade Visual

#### Paleta de Cores

| Nome | Código HEX | Uso Principal |
|------|------------|---------------|
| Primária | #007E85 | Botões, links, bordas |
| BlackLight | #1C1B1F | Bordas de inputs e placeholders |
| Neutro claro | #C3C3C3 | Textos principais |
| Black | #000000 | Textos principais |
| Error | #EE0202 | Erros, alertas críticoss |
| White | #FFFFFF | Backgrounds da tela e de cards |

#### 🖋️ Tipografia

| Tipo | Fonte Principal | Peso | Uso |
|------|----------------|------|-----|
| Títulos | Poppins | Bold | Textos principais |
| Corpo | Poppins | SemiBold | Textos botoes e links|
| Auxiliar | Poppins | Regular | Textos secundarios, fonte dos inputs |


### 🧱 Componentes UI

#### Botões

| Variante | Cor | Borda | Texto | Uso |
|----------|-----|-------|-------|-----|
| Primário | #2A9D8F | 4px | Branco | Ações principais (ex: criar conta, login confirmar) |
| Secundário | #EE0202 | 15px | Branco | Ações de exclusão e cancelamento |
| Desabilitado | #D1D5DB | Não | #9CA3AF | Estados inativos |

#### Inputs
- Bordas arredondadas 8px
- Altura: 66px
- Placeholder em cinza (#1C1B1F)
- Types: Text, Password, Email, Date, Select

#### Cards
- Fundo: #FFFFFF
- Borda: 1px sólida #007E85
- Bordas arredondadas 10px
- Espaçamento interno: 16px

### 🧭 Ícones
- Tamanho padrão: 24px
- Cores: herdam cor do texto

#### Tabela de Ícones do Sistema

| Ícone | Nome | Uso |
|-------|------|-----|
| ![Close Icon](images/Close%20Icon.png) | Fechar | Usado para fechar modais, popups e painéis |
| ![Variant2-1](images/Property%201=Variant2%20(1).png) | Home | Usado para navegar para a tela principal do sistema. |
| ![Variant2](images/Property%201=Variant2.png) | Home disable | Usado para indicar quando a tela principal do sistema nao estiver em foco |
| ![Variant2-3](images/Property%201=Variant2%20(3).png) | Consulta | Usado para navegar para a tela de agendamento de consulta |
| ![Variant2-5](images/Property%201=Variant2%20(5).png) | User | Usado para navegar para a de "perfil do usario". |
| ![Variant2-4](images/Property%201=Variant2%20(4).png) | User disable | Usado para indicar quando a tela de "perfil do usario"  nao estiver em foco |

### 👥 Jornada do Usuário

#### Médico
- Se cadastra
- Visualização da agenda de consulta
- Cancela agendamento

#### Paciente
- Se cadastra
- Agenda consulta
- Consulta agendamento
- Cancela agendamento

#### Admin
- Gerenciamento de agendamentos
- Emissão de relatórios
- Cancela Consulta


## 🛠️ Tecnologias

### Frontend
- **React**: Framework principal para desenvolvimento do frontend
- **Tailwind CSS**: Para estilização e design responsivo
- **Axios**: Para comunicação com a API

### Backend
- **Java com Spring Boot (versão 21)**: Framework principal para desenvolvimento do backend
- **JPA (Java Persistence API)**: Para comunicação com o banco de dados
- **Lombok**: Para reduzir a verbosidade do código

### Banco de Dados
- **PostgreSQL**: Banco de dados relacional principal
- **MongoDB**: Para armazenamento de logs e histórico de consultas

### Segurança
- **OAuth2**: Autenticação e autorização
- **HTTPS**: Comunicação segura
- **JWT (JSON Web Tokens)**: Gerenciamento de sessões

## 👥 Jornada do Usuário

### Médico
- Se cadastra
- Visualização da agenda de consulta
- Cancela agendamento

### Paciente
- Se cadastra
- Agenda consulta
- Consulta agendamento
- Cancela agendamento

### Administradir
- Gerenciamento de agendamentos
- Cadastro de pacientes
- Emissão de relatórios
- Gestão de especialidades médicas
