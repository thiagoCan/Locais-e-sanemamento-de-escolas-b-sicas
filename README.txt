1. Descrição breve (localização):

	Este é um trabalho de raspagem de dados, em que foi contado e montado um gráfico de barras duplas de escolas rurais e urbanas ao longo de cinco anos, entre 1995 e 1999. A linguagem de programação utilizada foi o python. Os arquivos lidos estavam na extenção "csv".
	
	1.1. Método utilizado:
	#read_csv()
		Exibe o arquivo ditado pelos parâmetros.

		
		parâmetros utilizados (filepath_or_buffer, usecols=[''], squeeze)

	#value_counts()
		Conta quantas vezes um valor é repetido.

	1.2. Parâmetros:
	#filepath_or_buffer
		Escreve-se o nome do arquivo com sua extenção entre aspas.
	
	#usecols
		Escreve-se qual coluna deseja-se exibir.

	#squeeze

		Este é um parâmetro booleano cujo padrão é False. Sendo False o jupyter notebook traz a tabela com a formatação do excel, mas não dá para trabalhar com os dados exibidos. Para se conseguir manipulá-los, deve-se alterar para squeeze=True.

Origem dos Dados usados:

	Os dados foram coletados do site <http://inep.gov.br/microdados> na guia "Censo Escolar". Lembrando que foram pegos os anos de 1995 a 1999.



Resultados obtidos (localização):

	Os resultados obtidos está no arquivo LocalizaçãoEsolas_R_U.ipynb