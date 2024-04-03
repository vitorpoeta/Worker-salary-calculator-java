## Sistema de Cálculo de Renda Mensal de Trabalhador

Este é um sistema em Java para calcular a renda mensal de um trabalhador com base em seu salário base e contratos por hora. O sistema é composto por diversas classes, incluindo `Worker`, `HourContract`, `WorkerLevel` (um enum), e um programa principal `Program`.

### Funcionalidades

- **Classe `Worker`**: Representa um trabalhador e inclui um método para calcular o rendimento mensal com base nos contratos de hora associados.
  
- **Classe `HourContract`**: Representa um contrato por hora, armazenando informações sobre a data, o valor por hora e a duração em horas.

- **Enumeração `WorkerLevel`**: Define os diferentes níveis de um trabalhador: JUNIOR, MID_LEVEL e SENIOR.

- **Programa Principal `Program`**: Interage com o usuário para inserir os contratos por hora do trabalhador e calcula a renda mensal com base nos contratos.

### Como Usar

1. **Configuração Inicial**: Importe as classes e enums necessários em seu projeto Java.

2. **Interagindo com o Usuário**: Execute o programa principal `Program` para inserir os contratos por hora do trabalhador. Siga as instruções fornecidas no console para inserir as informações necessárias para cada contrato.

3. **Visualizando a Renda Mensal**: Após inserir os contratos por hora, o programa calculará automaticamente a renda mensal do trabalhador para um ano e mês específicos. O resultado será exibido no console.

### Aprendizados

Este projeto proporciona uma oportunidade de aprendizado sobre:

- Organização de classes e pacotes em Java.
- Uso de enums para representar valores fixos relacionados.
- Manipulação de datas usando a classe `LocalDate`.
- Entrada de dados do usuário e processamento no console.
- Utilização de métodos de acesso e encapsulamento de atributos.
- Iteração em coleções e operações de soma condicional.

### Considerações Finais

O desenvolvimento deste sistema ajudou a consolidar o entendimento de conceitos fundamentais de programação em Java, bem como a prática na implementação de funcionalidades comuns em aplicativos do mundo real. A experiência adquirida neste projeto pode ser aplicada em projetos futuros para criar sistemas mais robustos e eficientes.
