# 🎓 Plataforma de Feedback Escolar

Uma plataforma que elimina a barreira de comunicação entre alunos, escolas e órgãos de gestão da educação, criando um canal direto, simples e seguro que transforma opiniões em ações concretas.

## 📋 Sobre o Projeto

A plataforma conecta alunos, escolas e órgãos da educação em um único ambiente digital, facilitando:

- **Feedbacks anônimos e seguros** dos alunos
- **Sugestões e elogios** de forma prática
- **Relatórios inteligentes** para tomada de decisões
- **Encaminhamento direto** de demandas aos órgãos responsáveis
- **Melhoria contínua** do ambiente escolar

Mais que uma ferramenta, é um movimento pela evolução da educação e pela valorização da voz do aluno.

## 🚀 Tecnologias Utilizadas

### Backend
- Java 21 <img src="https://skillicons.dev/icons?i=java" alt="Java"  width="25" height="25" style="margin-left: 10px;" />
- Spring Boot <img src="https://skillicons.dev/icons?i=spring" alt="Spring"  width="25" height="25" style="margin-left: 10px;" />
- PostgreSQL <img src="https://skillicons.dev/icons?i=postgresql" alt="PostgreSQL"  width="25" height="25" style="margin-left: 10px;" />

### Frontend
- React <img src="https://skillicons.dev/icons?i=react" alt="React"  width="25" height="25" style="margin-left: 10px;" />
- TailWind <img src="https://skillicons.dev/icons?i=tailwind" alt="Tailwind"  width="25" height="25" style="margin-left: 10px;" />

## 📦 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- **Java 21** ou superior
- **PostgreSQL** (versão 12 ou superior)
- **Maven** (para gerenciamento de dependências Java)
- **Git**

## ⚙️ Configuração do Banco de Dados

1. Instale o PostgreSQL em sua máquina
2. Crie um banco de dados para o projeto:
3. Configure as credenciais no arquivo.

## 🖥️ Instalação e Execução

1. Clone o repositório:
```bash
git clone ENDEREÇO REPOSITÓRIO
cd PASTA
```

### Backend (Java)

2. Configure o arquivo `src/main/resources/env`:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/Database
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
```

3. Execute o projeto com Maven (SE NECESSÁRIO):
```bash
./mvnw clean install
./mvnw spring-boot:run
```

Ou, se preferir usar o Maven instalado globalmente:
```bash
mvn clean install
mvn spring-boot:run
```

O backend estará rodando em `http://localhost:8080`

### Frontend (React)

1. Navegue até a pasta do frontend:
```bash
cd PASTA
```

2. Instale as dependências:
```bash
npm install
```

3. Configure as variáveis de ambiente criando um arquivo `.env`:
```env
VITE_BASE_URL=http://localhost:8080/api OU VERIFICAR SE ESTÁ VISIVEL O ENV .

Neste projeto, as variáveis de ambiente estão liberadas no repositório para facilitar a configuração e execução local.
```

4. Inicie o servidor de desenvolvimento:
```bash
npm start
```

O frontend estará rodando em `http://localhost:3000`

## 📁 Estrutura do Projeto
(BREVEMENTE ILUSTRATIVA, SUJEITO A MUDANÇAS)
```
edureport-base/
├── edureport-backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── resources/
│   │   └── test/
│   └── pom.xml
│   
├── edureport-frontend/
│   ├── public/
│   ├── src/
|   |   ├──api/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── Security/
│   │   └── App.js
│   └── package.json
│    
└── README.md
```


## 🌟 Funcionalidades Principais

- ✅ Envio de feedbacks anônimos
- ✅ Sistema de sugestões e elogios
- ✅ Painel administrativo para escolas
- ✅ Geração de relatórios inteligentes
- ✅ Encaminhamento de demandas
- ✅ Dashboard de análise de dados
- ✅ Autenticação e autorização segura

## 🤝 Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 👥 Desenvolvedores

Este projeto foi desenvolvido por:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Abreeu/">
        <img src="https://avatars.githubusercontent.com/u/98714169?s=96&v=4" width="100px;" alt="Foto Desenvolvedor 1"/><br>
        <sub>
          <b>Guilherme Abreu</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/gpmoraes82">
        <img src="https://avatars.githubusercontent.com/u/48733846?v=4" width="100px;" alt="Foto Desenvolvedor 2"/><br>
        <sub>
          <b>Gabriel P. Moraes</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Froener">
        <img src="https://avatars.githubusercontent.com/u/198973890?v=4" width="100px;" alt="Foto Desenvolvedor 3"/><br>
        <sub>
          <b>Henrique Froener</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/HugoBorrego">
        <img src="https://avatars.githubusercontent.com/u/182677843?v=4" width="100px;" alt="Foto Desenvolvedor 3"/><br>
        <sub>
          <b>Hugo Borrego</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Wbernard98">
        <img src="https://avatars.githubusercontent.com/u/94759624?v=4" width="100px;" alt="Foto Desenvolvedor 3"/><br>
        <sub>
          <b>Wellington Vargas Bernardes</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/gabrielspd">
        <img src="https://github.com/usuario3.png" width="100px;" alt="Foto Desenvolvedor 3"/><br>
        <sub>
          <b>Gabriel Senna</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/fmascena-dev">
        <img src="https://avatars.githubusercontent.com/u/172336180?v=4" width="100px;" alt="Foto Desenvolvedor 3"/><br>
        <sub>
          <b>Felipe Mascena Seabra</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


Desenvolvido com ❤️ para transformar a educação através da comunicação efetiva.
