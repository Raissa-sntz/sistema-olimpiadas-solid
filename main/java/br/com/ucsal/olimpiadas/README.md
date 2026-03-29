Sistema Olimpíadas - Refatoração SOLID

## Objetivo
Refatorar o sistema aplicando os princípios SOLID sem alterar a lógica original.

## Principais mudanças
* Separação de responsabilidades nas classes (Services)
* Criação da interface `CalculadoraNota`
* Organização do código em camadas (model e service)

## Princípios SOLID aplicados
### S - Single Responsibility Principle
Cada classe possui apenas uma responsabilidade.
Ex: `ParticipanteService`, `ProvaService`

### O - Open/Closed Principle
Uso da interface `CalculadoraNota` permite extensão sem modificar código existente.

### L - Liskov Substitution Principle
Implementações de `CalculadoraNota` podem ser substituídas sem quebrar o sistema.

### I - Interface Segregation Principle
Interfaces específicas foram utilizadas (ex: CalculadoraNota).

### D - Dependency Inversion Principle
Dependência de abstrações ao invés de implementações concretas.

## Restrições atendidas
* Não foi alterada a lógica de negócio original
* Nenhuma funcionalidade foi removida
* Nenhum framework externo foi utilizado
