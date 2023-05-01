from random import randint
from time import sleep
esron = voce = empate = 0
print('='*20)
print("Esron's Jokenpo!")
print('='*20)
for c in range(1, 4):
    itens = 'nulo', 'pedra', 'papel', 'tesoura'
    computador = randint(1,3)
    print(f'-----{c}ª rodada!-----')
    print('='*20)
    print('''[1] Pedra
[2] Papel
[3] Tesoura''')
    while True:
        jogador = int(input('Qual sua jogada? '))
        if 1 <= jogador <= 3:
            break
        print('Jogada inválida! Tente novamente.')
    print('JO')
    sleep(0.5)
    print('KEN')
    sleep(0.5)
    print('PO!')
    sleep(0.5)
    print(f'Você jogou: {itens[jogador]}')
    print(f'Esron jogou: {itens[computador]}')
    print('='*20)
    if jogador == 1:
        if computador == 1:
            print('Rodada empatada!')
            empate += 1
        elif computador == 2:
            print('Esron venceu a rodada!')
            esron += 1
        elif computador == 3:
            print('Você venceu a rodada!')
            voce += 1
    elif jogador == 2:
        if computador == 1:
            print('Você venceu a rodada!')
            voce += 1
        elif computador == 2:
            print('Rodada empatada!')
            empate += 1
        elif computador == 3:
            print('Esron venceu a rodada!')
            esron += 1
    elif jogador == 3:
        if computador == 1:
            print('Esron venceu a rodada!')
            esron += 1
        elif computador == 2:
            print('Você venceu a rodada!')
            voce +=1
        elif computador == 3:
            print('Rodada empatada!')
            empate += 1
    print('='*20)
    if empate == esron == voce == 1 or empate == 3:
        print('-----EMPATE!-----')
    if esron == 1 and empate == 2 or esron >= 2:
        print('-----DERROTA!-----')
    elif voce == 1 and empate == 2 or voce >= 2:
        print('-----VITÓRIA!-----')
