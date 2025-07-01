# MVP ANÁLISE DE DADOS E BOAS PRÁTICAS
Notebook criado exclusivamente para o MVP da disciplina de Análise de Dados

Aluno: Alex Joaquim Coelho

Dataset: Microdados do Censo Escolar da Educação Básica 2024 (INEP)

Onde encontrar o Dataset original: https://download.inep.gov.br/dados_abertos/microdados_censo_escolar_2024.zip Onde encontrar o Dataset usado aqui: https://github.com/ACOELHO1976/Analise_Exploratoria

Algumas observações: Tanto o arquivo CVS, quanto arquivos que ajudam a complemetar e entender mais do trabalho podem ser encontrados no endereço

# Dificuldade encontrada
O arquivo original é muito grande e com muitas colunas, mas muito rico em informações, e com uma boa quantidade de dados para análise. Diante disso, o arquivo a ser tratado nesse MVP (disponível no GitHub) é um "corte" do original, tanto em colunas quanto em dados.

# O Problema

Encontrar uma relação entre escolas da rede pública e privada, para tentar analisar as condições de infraestrutura dos locais, bem como a quantidade de pessoas matrículadas, idade, raça e gênero.

# Hipóteses do problema

Algumas das hipóteses levantas foram:

-  Quantidade de escolas por tipo de dependência, por estado.
-  Quantidade de escolas conforme sua localidade (zona urbana e rural), de acordo com a dependência.
-  Rancking dos 10 municípios com mais escolas no sudeste.
-  Quantidade de escolas conforme sua localidade.
-  Média de alunos por escola - estado, localização e dependência.
-  Quantidade de escolas com banheiro e que possuem banheiro PNE.
-  Quantidade de alunos matrículados por faixa etária.
-  Relação das escolas que tem cozinha e servem refeição.
-  Escolas com educação indígena, conforme os tipos de línguas ensinadas.

# Conclusão

A análise e pré-processamento do dataset do sendo escolar de 2024 se apresentou bastante rico em informações simples e muito conclusivas. O dataset é bem estruturado, pois sas informações são todas baseadas em respostas de SIM ou NÃO, estruturadas em 0 ou 1, tornando mais fácil a análise. Ao realizar a análise exploratória, ficou nítida que a apresentação dos dados já normalizados entre respostas simples de 0 ou 1, facilitou a análise. Apesar de saber que as etapas de normalização e padronização são fundamentais para preparar os dados para diversos algoritmos de aprendizado de máquina, o dataset escolhido não apresentou problemas como informações categorizadas ou ausências de informações que inviabilizasem as análises. Novamente aqui trago apenas a dificuldade encontrada em se trabalhar com um dataset muito grande, por isso fo adotado um "corte", analisando apenas sobre o aspecto da região Sudeste.

De todas as hipósteses levantas, que foram todas atendidas, ficou nítido a predominância do estado de São Paulo na gerição Sudeste, muito pelo seu próprio tamanho e a necessidade de atendimento de mais pessoas. Porém, ficou também demonstrado toda a dificuldade que a zona rural tem, tanto na quantidade de escolas, não importando de quem é a competência, quanto sobre a questão de infraestrutura.
