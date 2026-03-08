# project-scaffold-java

Scaffold arquitetural opinativo para projetos Java com separação clara de camadas, contratos explícitos e organização voltada para manutenção, testabilidade e evolução sustentável.

## Estrutura-base

- `docs/`: visão, arquitetura, ADRs e especificações
- `src/main/java/com/example/projectname/core/`: domínio puro
- `src/main/java/com/example/projectname/application/`: casos de uso e orquestração
- `src/main/java/com/example/projectname/contracts/`: DTOs, eventos, snapshots e contratos estruturais
- `src/main/java/com/example/projectname/infra/`: integrações e infraestrutura concreta
- `src/main/java/com/example/projectname/ui/`: CLI, web e presenters
- `src/test/java/com/example/projectname/`: testes unitários, de integração e e2e
- `tools/`: scripts e utilitários de engenharia

## Como usar

1. Substitua `com/example/projectname` pelo namespace real do projeto.
2. Escolha Maven ou Gradle como ferramenta de build.
