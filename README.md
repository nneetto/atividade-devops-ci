# Atividade Prática - Integração Contínua
## 1. Nome do aluno / dupla
Nome completo: Alberto Ferreira Carneiro/ Maycon Figueiredo

## 2. Repositório
Link:https://github.com/nneetto/atividade-devops-ci

## 3. Ferramentas utilizadas
- Git
- GitHub
- GitHub Actions
- Python
- Pytest

## 4. O que foi desenvolvido?
Foi desenvolvida uma pequena aplicação em Python contendo operações matemáticas simples (soma, subtração e multiplicação) para testar a integração.

## 5. Como funciona a pipeline?
Toda vez que um código é enviado git push, o GitHub Actions baixa o código, configura o Python, instala as dependências e roda os testes automaticamente para validar a aplicação.

## 6. Teste realizado
Foram criados 3 testes (test_soma, test_subtracao e test_multiplicacao).

## 7. Falha proposital
O operador matemático da função soma foi alterado de adição para subtração.

## 8. Resultado
Sim, a pipeline identificou o erro imediatamente e o status da Action mudou para FAIL.

## 9. Conclusão
A Integração Contínua serve para garantir que alterações no código sejam testadas automaticamente de forma rápida, evitando que erros cheguem ao ambiente final, evitando também que o código seja perdido por problemas físicos na maquina.
