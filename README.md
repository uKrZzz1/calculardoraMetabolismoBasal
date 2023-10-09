# Calculadora de Metabolismo Basal (MB)

O metabolismo basal (MB) é a quantidade mínima de energia que o corpo humano precisa para manter as funções vitais e outras atividades metabólicas básicas em completo repouso, em um ambiente termoneutro (temperatura ambiente confortável) e em estado de jejum.

# Utilidade do Calculo de Metabolismo Basal

1º Planejamento de Dieta e Exercício:
Saber o metabolismo basal ajuda a determinar a quantidade mínima de calorias que o corpo necessita para funcionar. Isso é fundamental para quem está tentando perder, ganhar ou manter o peso, pois permite calcular a ingestão calórica adequada.

2º Avaliação do Estado Nutricional:
Comparar o metabolismo basal com a ingestão calórica diária pode ajudar a avaliar se uma pessoa está consumindo calorias suficientes para sustentar as funções corporais básicas.

3º Prescrição Médica e Nutricional:
Em contextos clínicos, o metabolismo basal é calculado para determinar as necessidades energéticas de pacientes hospitalizados ou aqueles que estão se recuperando de doenças ou cirurgias. Isso é crucial para a prescrição de dietas adequadas e o monitoramento da nutrição durante o tratamento.

4º Avaliação do Progresso:
Para pessoas que estão tentando perder ou ganhar peso, calcular o metabolismo basal inicial e acompanhar as mudanças ao longo do tempo pode fornecer informações valiosas sobre o progresso e a eficácia de um programa de dieta e exercícios.

5º Ajuste de Calorias para Objetivos Específicos:
Atletas e fisiculturistas muitas vezes calculam o metabolismo basal para ajustar suas dietas e treinamentos, visando objetivos específicos de desempenho e composição corporal.

6º Avaliação do Gasto Calórico:
Além do metabolismo basal, o cálculo do metabolismo total inclui o gasto energético relacionado à atividade física e à termogênese induzida pela alimentação (energia necessária para digerir, absorver e processar os alimentos). Essas informações são essenciais para determinar o equilíbrio energético e ajudam a entender a relação entre a ingestão de calorias e o gasto calórico.

# Funcionalidade do código

O código para realizar o calculo foi realizado com javascrip e baseado na fórmula de Harris-Benedict, que é diferente para homens e mulheres.

Para calcular o MB necessita de quatro informações: Idade, Gênero, peso e altura. Apos preencher os campos com as mesma, ao clicar no botão "Calcular MB" ele chama a função calculateBMR.

Cada infromação é amarzenada na sua respectiva variavel, e para realizar a soma, a informação de gênero é utilizada em um teste logico sendo uma conta para o genêro masculino e outra para o feminino. Assim após o calculo ser concluido ele informa na tela o valor do seu MB.
