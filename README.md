# Hello World com Testes Unitários (.NET 10 & xUnit)

Repositório desenvolvido como atividade prática da disciplina de **Garantia da Qualidade de Software / Gestão e Qualidade de Software**.

---

## 👨‍🎓 Informações do Aluno

- **Disciplina:** Garantia da Qualidade de Software / Gestão e Qualidade de Software
- **Professor:** Daniel Henrique Matos de Paiva
- **Aluno:** Fernando Almeida de Oliveira Braga
- **RA:** 326132695

---

## 📌 Objetivo da Atividade

Criar uma solução .NET 10 via CLI (linha de comando), estruturar o projeto de aplicação e o projeto de testes com xUnit, vincular a referência entre ambos, implementar um método de saudação testável e versionar o código com Git/GitHub.

---

## 🛠️ Tecnologias Utilizadas

- **[.NET 10 SDK](https://dotnet.microsoft.com/)** (`net10.0`)
- **C#**
- **[xUnit](https://xunit.net/)** (Framework de testes unitários)
- **Licença MIT**

---

## 📂 Estrutura do Projeto

```text
├── LICENSE                        # Licença pública MIT
├── README.md                      # Documentação do projeto
└── olamundo-next-xunit/
    ├── MeuPrimeuiroTeste.slnx     # Arquivo de solução .NET
    ├── README.md                  # Documentação interna
    ├── MeuPrimeiroTeste.App/      # Projeto Console (Código de Produção)
    │   ├── Program.cs             # Ponto de entrada da aplicação
    │   ├── HelloWorldService.cs   # Implementação da regra de negócio / saudação
    │   └── MeuPrimeiroTeste.App.csproj
    └── MeuPrimeiroTeste.Tests/    # Projeto de Testes Unitários
        ├── HelloWorldServiceTests.cs  # Testes unitários com xUnit ([Fact], Assert)
        └── MeuPrimeiroTeste.Tests.csproj
```

---

## 🚀 Como Executar

### 1. Pré-requisitos
- Ter o [.NET 10 SDK](https://dotnet.microsoft.com/download) instalado na máquina.

Verifique com:
```bash
dotnet --version
```

---

### 2. Executar a Aplicação (Console)
```bash
dotnet run --project olamundo-next-xunit/MeuPrimeiroTeste.App/MeuPrimeiroTeste.App.csproj
```

---

### 3. Executar os Testes Unitários (xUnit)
Para rodar a suíte de testes e validar se todos os testes passaram:
```bash
dotnet test olamundo-next-xunit/MeuPrimeuiroTeste.slnx
```

Saída esperada:
```text
Aprovado!  – Com falha: 0, Aprovado: 1, Ignorado: 0, Total: 1
```

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).