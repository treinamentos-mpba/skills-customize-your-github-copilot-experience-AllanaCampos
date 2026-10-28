# 📘 Atividade: Data Cleaning and Validation with Pandas

## 🎯 Objetivo

Use Pandas para preparar um conjunto de dados imperfeito: identificar problemas, aplicar regras de limpeza e validar o resultado antes de exportá-lo.

## 📝 Tarefas

### 🛠️ Inspecionar e padronizar o dataset

#### Descrição
Carregue `data.csv` em um DataFrame e investigue sua estrutura antes de alterá-lo.

#### Requisitos
O programa concluído deve:

- Carregar o arquivo usando Pandas.
- Exibir o número de linhas e colunas, os tipos das colunas e a quantidade de valores ausentes por coluna.
- Contar as linhas duplicadas exatas.
- Remover espaços no início e no fim dos valores de texto.
- Remover as linhas duplicadas exatas e informar quantas foram removidas.

### 🛠️ Limpar valores ausentes e inválidos

#### Descrição
Aplique regras consistentes às colunas `grade`, `attendance_rate` e `club` para preparar os registros para análise.

#### Requisitos
O programa concluído deve:

- Converter `grade` e `attendance_rate` em valores numéricos; valores que não puderem ser convertidos devem ser tratados como ausentes.
- Remover registros com `grade` ausente ou fora do intervalo de 9 a 12 e converter as séries restantes para inteiros.
- Tratar valores de `attendance_rate` menores que 0 ou maiores que 1 como ausentes.
- Preencher valores ausentes em `attendance_rate` com a mediana dos valores válidos.
- Substituir valores ausentes ou vazios em `club` por `Sem clube`.

### 🛠️ Validar e exportar os dados limpos

#### Descrição
Verifique se as regras de limpeza foram cumpridas e salve o resultado em um novo arquivo CSV.

#### Requisitos
O programa concluído deve:

- Confirmar que não há linhas duplicadas nem valores ausentes no DataFrame final.
- Confirmar que todas as notas estão entre 9 e 12 e que todas as taxas de presença estão entre 0 e 1.
- Exibir as quantidades de registros antes e depois da limpeza.
- Exportar o resultado para `cleaned_students.csv`, sem incluir o índice do DataFrame como coluna.