# Desafio Prático
Este repositório tem como sua função a ideia de realizar práticas de versionamento de código. Através dele, podemos combinar as técnicas introduzidas durante as semanas para contribuir e tirar dúvidas sobre os comandos repassados.

## Comandos
Todas as ténicas e comandos foram repassados durante as reuniões com o material gravado e disponível para o time. Será possível consultar alguns dos comandos através deste [link](https://github.com/orgs/ISI-Automotiva/discussions/4).

## Boas Práticas
Lembrem-se de utilizas as boas práticas de mensagens de commits.

### Exemplos práticos para área de Dados:

*   **`feat:` (Funcionalidade/Feature)** - Para novas análises, novos scripts ou novas métricas.
    *   `feat: adiciona script de extração de dados da API do Salesforce`
    *   `feat: cria dashboard inicial de acompanhamento de vendas`

*   **`fix:` (Correção)** - Quando você arruma um erro em um script, query ou cálculo.
    *   `fix: corrige divisão por zero na métrica de churn rate`
    *   `fix: ajusta filtro de datas na query de clientes ativos`

*   **`docs:` (Documentação)** - Mudanças apenas na documentação (arquivos Markdown, dicionários de dados).
    *   `docs: atualiza dicionário de dados da tabela de transações`
    *   `docs: adiciona instruções de como rodar o Jupyter Notebook no README`

*   **`refactor:` (Refatoração)** - Quando você melhora o código sem alterar a regra de negócio final (muito comum ao otimizar queries).
    *   `refactor: otimiza CTE da query de vendas reduzindo tempo de execução em 50%`
    *   `refactor: move funções de limpeza de dados para um arquivo auxiliar utils.py`

*   **`chore:` (Manutenção)** - Tarefas de rotina, dependências ou configurações.
    *   `chore: atualiza versão da biblioteca pandas no requirements.txt`
    *   `chore: adiciona pasta de dados .csv ao .gitignore`