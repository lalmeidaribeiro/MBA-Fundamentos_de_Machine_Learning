# Análise de Evasão de Colaboradores - RH 

## Objetivo 
<p>O objetivo deste projeto é auxiliar a equipe de RH a identificar colaboradores que estão em risco de deixar a empresa. A proposta é fornecer uma análise preditiva que permita ao RH antecipar possíveis desligamentos e, assim, implementar ações de retenção antes que os funcionários optem por sair. O resultado esperado é um modelo capaz de estimar a probabilidade de saída de cada colaborado</p>

## Bibliotecas Utilizadas

- `pandas`
- `sklearn`
- `metplotlib`

## Descrição dos Atributos Disponíveis

- **nivel_satisfacao**: Nível de satisfação do funcionário com a empresa e seu cargo.
- **ult_avaliacao**: Nota atribuída pelo funcionário em sua última avaliação da empresa.
- **num_projetos**: Total de projetos nos quais o colaborador está envolvido atualmente.
- **media_horas_mes**: Média de horas trabalhadas pelo funcionário por mês.
- **tempo_empresa**: Tempo de permanência do colaborador na empresa (em anos).
- **aci_trabalho**: Indicador binário sobre ocorrência de acidente de trabalho (1 para sim, 0 para não).
- **saiu**: Indicador binário que informa se o colaborador deixou a empresa (1 para saiu, 0 para ainda empregado).
- **promocao_ult_5anos**: Indicador binário que mostra se o colaborador foi promovido nos últimos cinco anos (1 para sim, 0 para não).
- **departamento**: Departamento ao qual o colaborador pertence (sales, technical, support, IT, product_mng, marketing, RandD, accounting, hr, management).
- **salario**: Categoria salarial do colaborador (low, medium, high).

## Tecnologias Utilizadas
- `Google Colab`

## Como Executar o Modelo

1. Baixe o modelo preditivo disponível.
2. Escolha uma ferramenta para manipulação do código (recomenda-se `Google Colab` ou `Jupyter Notebook`).
3. Salve a base de dados disponível na pasta **bases/** junto com o modelo preditivo.
4. Execute o código passo a passo para rodar o modelo e visualizar os resultados.