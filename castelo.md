#exercício2#

print ("Bem-vindo ao TOUR no castelo")
print ("Já estamos no portão.\n Vamos comerçar?")
print (" digite 1 para ir para a sala do trono")
print (" digite qualquer tecla para ir para o salão de festas")

escolha = input ("para onde você quer ir?......... ")

if escolha == "1":
    proximo = "sala do trono" 
else:
    proximo = "salão de festas" 

if proximo == "sala do trono":
   print ("você chegou agora na sala do trono!")
   print ("qual caminho você quer escolher?")
   print ("digite 1 para suíte real")
   print ("digite qualquer tecla para ir para o calabouço")
   escolha = input ("digite sua escolha:...........  ")
   if escolha == "1":
       proximo = "suíte real"
   else:
        proximo = "calabouço"

if proximo == "salão de festas":
    print ("você chegou no salão de festas!")
    print ("qual caminho agora você quer escolher?")
    print ("digite 1 para calabouço")
    print ("digite qualquer tecla para ir para a masmorra")
    escolha = input ("digite sua escolha:............  ")
    if escolha == "1":
        proximo = "calabouço"
    else:
        proximo = "masmorra"

if proximo ==  "calabouço":
    print ("você escolheu o caminho do calabouço!")
    print ("agora você está no pátio")
    print ("e você deve ir para a torre")
    escolha = input ("digite sim para ir para a torre...  ")
    if escolha == "sim":
        proximo = "torre"
        print ("você chegou na torre!")
        print ("fim de jogo")
    else:
        print ("não tem saída")

if proximo ==  "suíte real":
    print ("você escolheu o caminho da suíte real!")
    print ("agora você está no pátio")
    print ("e você deve ir para a torre")
    escolha = input ("digite sim para ir para a torre...  ")
    if escolha == "sim":
        proximo = "torre"
        print ("você chegou na torre!")
        print ("fim de jogo")
    else:
        print ("não tem saída")

if  proximo == "masmorra":
    print ("você chegou na masmorra!")
    print ("você pode ir para o pátio ou torre")
    print ("digite 1 para pátio")
    print ("digite qualquer tecla para ir para a torre")
    escolha = input ("digite sua escolha:...............  ")
    if escolha == "1":
        proximo = "pátio"
    else:
        proximo = "torre"
        print ("você chegou na torre!")
        print ("fim de jogo")

if proximo == "pátio":
    print ("você chegou no pátio!")
    print ("e você deve ir para a torre")
    escolha = input ("digite sim para ir para a torre...  ")
    if escolha == "sim":
        proximo = "torre"
        print ("você chegou na torre!")
        print ("fim de jogo")
        
    else:
        print ("fim de jogo")









