## Bot da Azure IA
Esse projeto se dá a necessidade de resultados, 
	onde quando há um numero enorme de respostas em pesquisas

Para agilizarmos tempo e trazermos um filtro especifico, utilizamos dessa IA

Bot do Azure
	Quando precisamos dar um retorno de algum serviço 

	Antigamente quando precisavamos de alguma ajuda, era retornado algumas opções
		[
			1 - para servico 1
			2 - para servico 2
			3 - para falar com atendente
		]

	Atualmente com essa evoluçao do BOT, conseguimos conversar com um bot e atraves de algumas palavras chaves, ele ja nos da o que precisamos, muitas vezes sem nem precisar passar por um especialista

	Lógico, devemos sempre atualizar a memoria/base de dados dele, testando e validando

	Sempre tendo a conectividade baseada em nuvem mas atraves de varios canais, WPP, App, Telefone, Site

	Linguagem Coloquial
		Assim como um comando Acenda a Luz, Me diga a previsão do tempo
			Eles sao formados por uma ação, e um objeto/entidade 
				[Acenda a] - Uma ação que por si só nao justifica muito
				[Luz] - Um Objeto que por si só é, Ok e...
					Quando juntados, temos a informação completa para realizar uma tarefa

					Lembrando que luz, nós sabemos oq é uma luz, mas precisamos ensinar a maquina o que é isso, até por que sempre vem lançando novos dispositivos

						"Ligar um Ar Condicionado"

	Dentro do Azure, tambem temos API de conversão de Fala em Texto, e Texto em Fala
		Dito isso, podemos tilizar recursos de conversao de fala em texto, de forma "audível", com clareza, para que o bot entenda e faça uma ação

		E a de Texto em Fala para pessoas que tem dificuldade ou deficiencia em ler textos, pedindo a transcrição daquele texto

	
Maos na massa
	Dentro do site https://speech.microsoft.com/portal
		Dentro dele, abrir a aba de configurações 
			Criar novo recurso

			Depois de criado ele estara na aba de recursos, lembrar sempre de colocar o serviço que quer utilizar 

		Novamente no portal,
			CONVERSAO TEXTO EM FALA EM TEMPO REAL
				Idioma do audio/midia que quer enviar para transformar em texto

				Necessario sempre entender e buscar o que faz mais sentido para aquela função em específico (Por exemplo, transcrição de uma ligação de Call Center, uma reuniao em outro idioma (Já que ele faz a transcrição em tempo real))

				Lembrando de sempre verificar quanto custará tal aplicação


	Entrando na aba portal.azure.com/#Home
		Em "IA + Machine Learning" >>> LANGUAGE SERVICE 
			Colocando todas as abas necessarias das Features
				Nome | Free F0 30 dias free
				Review para verificar se tem creditos (COMO É FREE, É FREE)

			Nesse serviço, colocando uma avaliação negativa como teste
				Testando ele retorna qual o sentimento Positivo, Neutro, Negativo, 

			Tendo isso em vista conseguimos implementar isso num lançamento de um prosduto ou em uma pesquyisa, 

			Pois ele faz uma analise de sentimentos e retorna uma estatistica conforme o texto escrito

## IA Generativa COPILOT e OPENAI

	Passos necessarios quando trabalhamos com uma IA

		Identificar
			Quando podemos ver possiveis danos para a solução planejada

		Medida
			Planejar medidas para esses danos saindo pelas soluções

		Mitigar
			Filtrar em varias camadas esses danos para minimizar os impactos

		Operar
			Solução com resposabilidade definindo e seguindo com plano de implantação e preparação operacional

	Trabalhando com COPILOT
		Quando trabalhamos com essa IA, conseguimos gerar respostas gerar imagens, geração de codigos e muito mais.

