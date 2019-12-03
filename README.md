def radar():
    from math import sqrt
    from time import sleep
    velo = int(input('\033[1;32mDigite a sua velocidade: \033[m'))  
    print('\033[1;33mAnalizando....\033[m')
    sleep(1)
    if velo <= 80:
        print('\033[1;32mVelocidade permitida, siga em frente !!! \033[m')
    elif velo <= 120:
        calc1 = velo * 1 -80
        print('\033[1;31mVocê foi multado !!! \n Multa de R$: {:.2f}\033[m'.format(calc1))
    else:
        calc2 = velo * 1 -80
        print('Quer morrer !!! \n Multa de R$:{:.2f}'.format(calc2))
radar()
radar()
radar()
radar()
