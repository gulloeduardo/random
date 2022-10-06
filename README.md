from random import choice
v1 = 'Já beijou na boca?'
v2 = 'Já bebeu cerveja?'
v3 = 'Já ficou bêbado?'
v4 = 'Já caiu da escada, se sim quando?'
d1 = 'Imitar um gorila'
d2 = 'Beijar o chão'
d3 = 'Plantar bananeira'
d4 = 'Ligar para a mãe do seu melhor amigo'
Lista_v = [v1, v2, v3, v4]
Lista_d = [d1, d2, d3, d4]
escolha = (input('Caso queira verdade escreva v, caso queira desafio escreva d: '))
v = choice(Lista_v)
d = choice(Lista_d)
if'v' == escolha:print((f'{v}'))
else: print(f'{d}')
