nota1=float(input('digite a primeira nota: '))
nota2=float(input('digite a segunda nota: '))
nota3=float(input('digite a terceira nota: '))
nota4=float(input('digite a quarta nota: '))
notas=(nota1+nota2+nota3+nota4)/4
if notas >=9 and notas<=10:
    print('\033[34mA')
elif notas >=7 and notas <9:
    print('\033[32mB')
elif notas >=5 and notas < 7:
    print('\033[33mC')
else:
    print('\033[31mReprovado')
