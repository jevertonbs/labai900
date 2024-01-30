## LAB AI 900 ##
Farei um passo a passo bem resumido do primeiro lab da AzureML com o teste de previsão aluguel de bicicletas, que pode ser acessado através do link: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

Crie um Espaço de Trabalho no Azure Machine Learning:

# Acesse o Portal Azure com suas credenciais.
Selecione "+ Criar um recurso", pesquise "Machine Learning" e crie um novo recurso do Azure Machine Learning com configurações específicas.
Aguarde a criação do espaço de trabalho.

# Acesse o Azure Machine Learning Studio:

Selecione "Launch Studio" no recurso criado ou vá para https://ml.azure.com.
No estúdio, visualize seu espaço de trabalho.

# Use Aprendizado de Máquina Automatizado para Treinar um Modelo:

Vá para a página Automated ML (em Authoring).
Crie um novo trabalho de ML automatizado com configurações específicas, incluindo tipo de tarefa, conjunto de dados, métricas, modelos permitidos, etc.
Envie o trabalho de treinamento e aguarde a conclusão.

# Avalie o Melhor Modelo:

Na guia Visão geral do trabalho automatizado, observe o melhor resumo do modelo.
Selecione o nome do algoritmo do melhor modelo para visualizar detalhes.
Revise métricas e gráficos de desempenho.

# Implante e Teste o Modelo:

Na guia Modelo do melhor modelo, selecione "Implantar" e use a opção de serviço Web.
Aguarde a implantação e teste o serviço usando dados de entrada específicos.

# Limpeza (Opcional):

Se não pretender usar o serviço, exclua o ponto de extremidade para evitar custos desnecessários.
Se terminou de explorar o Azure Machine Learning, pode excluir o espaço de trabalho e recursos associados no Portal Azure.
Lembre-se de substituir os valores fictícios pelos valores reais necessários. Este é um guia resumido, consulte a documentação do Azure para detalhes completos e atualizados.
