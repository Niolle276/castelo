#exercício3#

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
   print ("Que sorte, você encontrou uma armadura")
   armadura = 20
   print ("qual caminho você quer escolher?")
   print ("digite 1 para suíte real")
   print ("digite qualquer tecla para ir para o calabouço")
   escolha = input ("digite sua escolha:...........  ")
   if escolha == "1":
       proximo = "suíte real"
   else:
        proximo = "calabouço"

if  proximo ==  "calabouço":
    print ("você escolheu o caminho do calabouço!")
    print ("que sorte, você encontrou uma espada")
    espada = 10
    print ("agora você está no pátio")
    print ("que sorte, você encontoru um capacete")
    capacete = 5
    print ("e você deve ir para a torre")
    escolha = input ("digite sim para ir para a torre...  ")
    if escolha == "sim":
        proximo = "torre"
        print ("você chegou na torre!")
        pontos = armadura + espada + capacete
        print ("Neste tour você conseguiu 30 pontos")
        print ("fim de jogo")
    else:
        print ("você não tem saída")

if proximo == "salão de festas":
    print ("você chegou no salão de festas!")
    print ("que sorte, você encontrou um escudo")
    escudo = 5
    print ("qual caminho agora você quer escolher?")
    print ("digite 1 para calabouço")
    print ("digite qualquer tecla para ir para a masmorra")
    escolha = input ("digite sua escolha:............  ")
    if escolha == "1":
        proximo = "calabouço"
    else:
        proximo = "masmorra"

if  proximo ==  "calabouço":
    print ("você escolheu o caminho do calabouço!")
    print ("que sorte, você encontrou uma espada")
    espada = 10
    print ("agora você está no pátio")
    print ("que sorte, você encontoru um capacete")
    capacete = 5
    print ("e você deve ir para a torre")
    escolha = input ("digite sim para ir para a torre...  ")
    if escolha == "sim":
        proximo = "torre"
        print ("você chegou na torre!")
        pontos = escudo + espada + capacete
        print ("Neste tour você conseguiu 20 pontos")
        print ("fim de jogo")
    else:
        print ("não tem saída")

if proximo ==  "suíte real":
    print ("você escolheu o caminho da suíte real!")
    print ("agora você está no pátio")
    print ("que sorte, você encontoru um capacete")
    capacete = 5
    print ("e você deve ir para a torre")
    escolha = input ("digite sim para ir para a torre...  ")
    if escolha == "sim":
        proximo = "torre"
        print ("você chegou na torre!")
        pontos = armadura + capacete
        print ("Neste tour você conseguiu 25 pontos")
        print ("fim de jogo")
    else:
        print ("não tem saída")

if  proximo == "masmorra":
    print ("você chegou na masmorra!")
    print ("que sorte, você encontrou uma lança")
    lanca = 15
    print ("você pode ir para o pátio ou torre")
    print ("digite 1 para pátio")
    print ("digite qualquer tecla para ir para a torre")
    escolha = input ("digite sua escolha:...............  ")
    if escolha == "1":
        proximo = "pátio"
    else:
        proximo = "torre"
        pontos = escudo + lanca 
        print ("Neste tour você conseguiu 20 pontos ")
        print ("você chegou na torre!")
        print ("fim de jogo")

if proximo == "pátio":
    print ("você chegou no pátio!")
    print ("que sorte, você encontrou um capacete")
    capacete = 5
    print ("e você deve ir para a torre")
    escolha = input ("digite sim para ir para a torre...  ")
    if escolha == "sim":
        proximo = "torre"
        print ("você chegou na torre!")
        pontos = escudo + lanca + capacete
        print ("Neste tour você conseguiu 25 pontos")
        print ("fim de jogo")
        
    else:
        print ("fim de jogo")






