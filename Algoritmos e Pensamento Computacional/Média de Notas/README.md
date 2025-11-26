# SISTEMA DE GERENCIAMENTO DE ALUNOS
Este projeto é um sistema de gerenciamento de alunos desenvolvido em linguagem C que permite cadastrar estudantes, inserir suas notas e calcular automaticamente a média, informando se o aluno foi aprovado ou reprovado. O sistema utiliza alocação dinâmica de memória e permite o cadastro de múltiplos alunos.

## Tecnologias e Recursos Utilizados
**Linguagem:** C

**Bibliotecas padrão:**
- `<stdio.h>` — entrada e saída de dados
- `<stdlib.h>` — alocação dinâmica de memória
- `<string.h>` — manipulação de strings

**Estruturas de dados:**
- `struct Estudante` — armazena dados do aluno (nome, matrícula, nota média)
- Ponteiros (`float*`) — alocação dinâmica para armazenar quantidade variável de notas

**Gerenciamento de memória:**
- `malloc()` — alocação dinâmica de memória
- `free()` — liberação de memória alocada

**Estruturas de controle:**
- `do-while` — loop principal do sistema
- `for` — loop para inserção de múltiplas notas
- `if-else` — validação de entrada e verificação de aprovação/reprovação

**Tratamento de erros:**
- Validação de número de notas (não aceita valores <= 0)
- Verificação de erro na alocação de memória

**Compilador:** GCC

## Como usar este projeto?

### 1. Download
Baixe o arquivo do código-fonte deste repositório.

### 2. Abrir na IDE ou ONLINE (GDB)
- Abra o arquivo no Dev-C++, Code::Blocks, Visual Studio ou sua IDE de preferência
- Certifique-se de que a IDE está configurada para usar um compilador C

### 3. Compilar e Executar
- Compile o projeto
- Execute o programa

## Exemplos de Uso:

**Exemplo 1: Cadastro com aprovação**
```
Digite o nome do estudante: João
Digite a matricula do aluno: 12345
Digite o numero de notas que deseja inserir: 3
Serão inseridas 3 notas:
Digite a 1 nota: 7.5
Digite a 2 nota: 8.0
Digite a 3 nota: 6.5

Resultado do Estudante
Nome: João
Matrícula: 12345
Média: 7.33
Estudante aprovado!
```
**Exemplo 2: Cadastro com reprovação**
```
Digite o nome do estudante: Maria
Digite a matricula do aluno: 54321
Digite o numero de notas que deseja inserir: 2
Serão inseridas 2 notas:
Digite a 1 nota: 4.0
Digite a 2 nota: 5.5

Resultado do Estudante
Nome: Maria
Matrícula: 54321
Média: 4.75
Estudante reprovado!
```
## Informações adicionais:
O programa utiliza um loop `do-while`, permitindo que o usuário cadastre vários estudantes sem reiniciar o sistema. Para sair, basta responder "n" quando perguntado se deseja cadastrar outro estudante.

O sistema possui **alocação dinâmica de memória**, permitindo que o usuário defina quantas notas deseja inserir para cada aluno, otimizando o uso de recursos.

**Critério de aprovação:** Média >= 6.0

**O código possui tratamento para erros:**
1. Validação de número de notas inválido (valores negativos ou zero)
2. Verificação de falha na alocação de memória
