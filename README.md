# 🔧 Oficina C# do Borracheiro de Código 🔧

![C#](https://img.shields.io/badge/C%23-11.0-blueviolet?logo=c-sharp&style=for-the-badge)
![.NET](https://img.shields.io/badge/.NET-8.0-blue?logo=dotnet&style=for-the-badge)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-2022-5C2D91?logo=visual-studio&style=for-the-badge)

Bem-vindo ao meu "box" de aprendizado! Este repositório é onde estou guardando minhas ferramentas, peças e experimentos enquanto "calibro" minhas habilidades em **C#** e no ecossistema **.NET**.

Como um "Borracheiro de Código", meu objetivo aqui é aprender a diagnosticar problemas, consertar "vazamentos" lógicos e construir soluções robustas, começando do básico.

---

## 🏁 Objetivo Atual do Projeto

O projeto `ExemplosCodigo` é minha primeira "inspeção" na **Programação Orientada a Objetos (POO)**.

O objetivo principal é demonstrar o "alinhamento" básico entre o ponto de entrada de um programa e uma classe auxiliar:

1.  **O "Gerente" (`Program.cs`):** É o ponto de entrada principal da aplicação. Ele orquestra o trabalho.
2.  **O "Especialista" (`Exemplo01.cs`):** É uma classe separada que tem uma responsabilidade específica (neste caso, exibir uma mensagem).
3.  **A "Ordem de Serviço":** O `Program.cs` **instancia** (cria) um objeto do tipo `Exemplo01` e **chama** seu método `ExibirMensagem()`.

## 🛠️ Bancada de Ferramentas (Tecnologias)

* **Linguagem:** C# 11
* **Plataforma:** .NET 8.0 (Console App)
* **IDE:** Visual Studio 2022
* **Controle de Versão:** Git & GitHub

## 🚗 Dando a Partida (Como Executar)

Você pode "ligar" este projeto e ver o motor funcionando.

### Pré-requisitos (O que você precisa na sua garagem)

* [.NET 8.0 SDK (ou superior)](https://dotnet.microsoft.com/download)
* [Visual Studio 2022 Community (ou superior)](https://visualstudio.microsoft.com/vs/community/)
* [Git](https://git-scm.com/downloads)

### Ligando o Motor

1.  **Clone o repositório** para sua máquina local:
    ```bash
    git clone [https://github.com/SEU-USUARIO-GITHUB/ExemplosCodigo.git](https://github.com/SEU-USUARIO-GITHUB/ExemplosCodigo.git)
    ```

2.  **Abra a Solução** no Visual Studio 2022:
    * Navegue até a pasta clonada e abra o arquivo `ExemplosCSharp.sln`.

3.  **Execute o Programa:**
    * Pressione **Ctrl + F5** (Iniciar sem Depuração) ou clique no botão (▶) "Play".
    * Um console aparecerá, mostrando a mensagem executada a partir da classe `Exemplo01`!

## ⚙️ Inventário de Peças (Estrutura do Projeto)

Aqui está um mapa de como a oficina está organizada:

```sh
ExemplosCSharp/                  # A "Oficina" completa (A Solução .sln)
│
├── ExemplosCodigo/              # O "Box" principal (O Projeto .csproj)
│   │
│   ├── Exemplo01.cs             # A "Ferramenta Especialista" (Nossa classe)
│   │
│   ├── Program.cs               # O "Gerente" (Ponto de entrada do Console)
│   │
│   └── ExemplosCodigo.csproj    # O manifesto do projeto (configurações, etc.)
│
├── .gitignore                   # O "Porteiro" (lista o que não vai para a nuvem)
│
└── README.md                    # O "Manual da Oficina" (Este arquivo)
