# S.G.I.E - Sistema de Gestão Integrada Escolar

O S.G.I.E é uma plataforma desenvolvida para centralizar e automatizar a gestão de instituições de ensino, abrangendo desde o controle acadêmico até a comunicação com os responsáveis.

## 🚀 Tecnologias
* **Backend:** .NET 8 (C#)
* **Banco de Dados:** PostgreSQL
* **Ferramentas:** Entity Framework Core, Swagger (OpenAPI)
* **Monitoramento:** Integração com bot de Telegram para alertas de status (NOC)

## 🛠️ Funcionalidades (Em desenvolvimento)
- [ ] Arquitetura base do sistema em .NET
- [x] Modelagem do banco de dados (PostgreSQL)
- [ ] Módulo de gestão de alunos e professores
- [ ] Sistema de lançamento de notas e frequências
- [ ] Dashboard administrativo
- [ ] Geração de PDF das carteirinhas para impressão

## 🔧 Como rodar o projeto localmente
1. Clone o repositório: `git clone https://github.com/4lur/sgie.git`
2. Certifique-se de ter o **SDK do .NET 8** instalado.
3. Configure a string de conexão do PostgreSQL no `appsettings.json`.
4. Execute as migrations: `dotnet ef database update`.
5. Inicie a aplicação: `dotnet run`.
