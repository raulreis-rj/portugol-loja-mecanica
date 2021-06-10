# portugol-loja-mecanica
Código de uma loja de mecânica
programa
{
	
	funcao inicio()
	{
		
		cadeia nome
		inteiro op,qtd
		real valor_produto,valor_total
		escreva("Bem vindo ao OficinaApp\n")
		escreva("\n")
		escreva("Digite aqui seu nome: ")
		leia(nome)
		escreva("Bem vindo ",nome, "\n")
		escreva("\n")
		escreva("Confira os produtos que temos e seus preços\n")
		escreva("---------------Tabela---------------------\n")
          escreva("1-PARAFUSO -------------------0,60\n")
          escreva("2-PORCA    -------------------0,30\n")
          escreva("3-ARRUELA  -------------------0,15\n")
          escreva("\n")
          escreva("Digite a opção que deseja comprar: ")
          leia(op)

				se(op==1)
				{
					escreva("Você escolheu a opção 1-PARAFUSO ---------R$ 0,60 \n\n")
					escreva("Digite aqui a quantidade que você quer: \n")
					leia (qtd)
					

					valor_produto=0.60*qtd

					escreva("O valor é de R$ ",valor_produto,"\n\n")
					escreva ("Você como é nosso cliente tem 30 % de desconto sobre o produto.\n\n")
					valor_total=valor_produto-valor_produto*0.30
					escreva (nome," você comprou ",qtd," PARAFUSOS, então o valor total é de R$",valor_total,"\n\n")
					
					
					
				}
					se(op==2)
					{
						escreva("Você escolheu a opção 2-PORCA ---------R$ 0,30 \n\n")
						escreva("Digite aqui a quantidade que você quer: \n")
						leia (qtd)
						
	
						valor_produto=0.30*qtd
	
						escreva("O valor é de R$ ",valor_produto,"\n\n")
						escreva ("Você como é nosso cliente tem 20 % de desconto sobre o produto.\n\n")
						valor_total=valor_produto-valor_produto*0.20
						escreva (nome," você comprou ",qtd," PORCA, então o valor total é de R$",valor_total,"\n\n")
						
						
						
					}
							se(op==3)
						{
							escreva("Você escolheu a opção 3-Arruelas ---------R$ 0,15 \n\n")
							escreva("Digite aqui a quantidade que você quer: \n")
							leia (qtd)
							
		
							valor_produto=0.15*qtd
		
							escreva("O valor é de R$ ",valor_produto,"\n\n")
							escreva ("Você como é nosso cliente tem 10 % de desconto sobre o produto.\n\n")
							valor_total=valor_produto-valor_produto*0.10
							escreva (nome," você comprou ",qtd," ARRUELAS, então o valor total é de R$",valor_total,"\n\n")
							
							
							
						}
						senao{
						 escreva("Opção inválida,informe corretamente a opção.")
						}
          
	}
}
