# Candidatura

Este é um programa Java que simula um processo de candidatura para uma vaga de emprego. Ele aborda várias etapas do processo, desde a tentativa de contato com os candidatos até a seleção com base nos salários pretendidos.

## Funcionalidades

### Entrando em Contato

- O programa tenta entrar em contato com os candidatos da lista.
- Cada candidato é contatado até 3 tentativas ou até que atenda a ligação.
- Se o contato for bem-sucedido, uma mensagem é exibida indicando o sucesso.
- Se o contato não for bem-sucedido após 3 tentativas, uma mensagem é exibida indicando o número máximo de tentativas.

### Seleção de Candidatos

- O programa simula a seleção de candidatos com base em seus salários pretendidos.
- É estabelecido um limite de 5 candidatos selecionados.
- Os candidatos são avaliados de acordo com seus salários pretendidos em relação a um salário base.
- Os candidatos selecionados e não selecionados são indicados com mensagens apropriadas.

## Notas Adicionais

- A classe `candidatura` contém um método `main` que inicia o processo de candidatura.
- O método `entrandoEmContato` simula a tentativa de contato com um candidato.
- O método `atender` simula a resposta de um candidato ao telefone.
- O método `selecaoCandidatos` simula a seleção de candidatos com base nos salários pretendidos.
- O método `valorPretendido` gera um valor de salário pretendido aleatório.
- O método `analisarCandidato` avalia um candidato com base em seu salário pretendido.

## Observações

Este programa é uma simulação e não reflete um processo de candidatura real. Foi criado apenas para fins de demonstração e aprendizado. Os valores e comportamentos são fictícios e podem não representar situações reais de recrutamento e seleção.
