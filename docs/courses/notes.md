# Notes 👀

## Tipos de Projetos

```text
└── 💻 src/                      # Projetos e aplicações práticas.
    ├── console/                 # Aplicações de linha de comando (Console)
    ├── api/                     # APIs RESTful com ASP.NET Core (Web API)
    ├── app/                     # Aplicações Web com UI (MVC/Razor Pages)
    ├── blazor/                  # Aplicações Web interativas com Blazor
    ├── console/                 # Aplicações de linha de comando (Console)
    ├── library/                 # Bibliotecas de código reutilizável (Class Library)
    ├── maui/                    # Aplicações nativas (Desktop/Mobile) com .NET MAUI
    └── tests/                   # Projetos de testes automatizados (xUnit, etc.)
    └── worker/                  # Serviços de background e tarefas agendadas
```

Últimas adições, com uma breve explicação do porquê são relevantes para iniciantes:

- Worker Service (worker): Este é o modelo ideal para criar serviços de background. Pense em tarefas que precisam rodar continuamente ou em intervalos agendados, como processar e-mails em uma fila, gerar relatórios noturnos ou monitorar um recurso. Para um iniciante, é um passo natural depois de um aplicativo de console, introduzindo conceitos importantes como o Host Genérico e Injeção de Dependência em um contexto mais simples que o de uma API web.

- Blazor (blazor): Enquanto **MVC** e **Razor Pages** são ótimos para aplicações web tradicionais, **Blazor** é a tecnologia da Microsoft para criar interfaces web interativas e ricas com C#. Em vez de depender majoritariamente de JavaScript, você pode construir componentes de UI reutilizáveis usando a linguagem que já está aprendendo. É fundamental para quem quer desenvolver aplicações web modernas no ecossistema .NET.

- .NET MAUI (maui): Este é o framework para criar **aplicativos nativos para desktop (Windows, macOS) e mobile (iOS, Android)** a partir de uma única base de código C#. Para um iniciante que sonha em criar um aplicativo para celular ou um programa para instalar no computador, o MAUI é o caminho moderno e oficial dentro da plataforma .NET.

## Sugestões de conteúdos

- Crie um novo arquivo em `docs/` chamado `blazor-vs-mvc.md` explicando as diferenças entre Blazor e MVC para um iniciante.

- **string verbatim**, prefixada com o símbolo `@`.
Uma string verbatim ignora todas as sequências de escape, tratando cada caractere como um literal.
- conversão de tipo implícita e explícita

## Mkdocs

Links para pesquisar e descobrir...

- [https://www.mkdocs.org](https://www.mkdocs.org)

### Meu Mkdocs com GitHub Pages

- [https://heviane.github.io/dotnet-lab/](https://heviane.github.io/dotnet-lab/)

MkDocs é uma ferramenta que transforma arquivos de texto simples, escritos em Markdown (.md), em um site de documentação com aparência profissional.

Pense nele como um "construtor de sites" para documentação. Em vez de escrever HTML e CSS complexos, você foca no conteúdo em Markdown, e o MkDocs cuida de todo o resto, gerando um site estático, rápido e fácil de hospedar em qualquer lugar (como o GitHub Pages).

Em resumo:

Entrada: Arquivos de texto em Markdown (.md).
Processo: O MkDocs lê esses arquivos.
Saída: Um site HTML completo e navegável.
É a ferramenta que está por trás da construção do seu site de documentação, conforme definido no seu workflow do GitHub Actions.
