import math
print("""
1 - pola
2 - obwody
3 - objetosci
4 - pola powierzchni
5 - inne""")
inp = input()
if inp == '1':
 print("""
 1 - pole kwadratu
 2 - pole prostokatu
 3 - pole rownolegloboku
 4 - pole trapezu
 5 - pole trojkata
 6 - pole trojkata rownobocznego
 7 - pole kola
 8 - pole rombu
 9 -przekatne rombu""")
 inp = input()
 if inp == 'a':
  a = float(input("1 = "))
  print(f'pole kwadratu wynosi {a**2}')
 elif inp == '2':
  a = float(input("a = "))
  b = float(input("b = "))
  print(f'pole prostokatu wynosi {a * b}')
 elif inp == '3':
  a = float(input("a = "))
  h = float(input("h = "))
  print(f'pole rownolegloboku wynosi {a * h}')
 elif inp == "4":
  a = float(input("a = "))
  b = float(input("b = "))
  h = float(input("h = "))
  print(f'pole trapezu wynosi {((a + b) * h) / 2}')
 elif inp == "5":
  a = float(input("a = "))
  h = float(input("h = "))
  print(f'pole trojkata wynosi {(a* h) / 2}')
 elif inp == "6":
  a = float(input("a = "))
  print(f'pole trojkata rownobocznego wynosi {(a**2 * math.sqrt(3)/4)}')
 elif inp == "7":
  r = float(input("r = "))
  print(f'pole kola wynosi {math.pi * r**2}')
 elif inp == "8":
  a = float(input("a = "))
  h = float(input("h = "))
  print(f'pole rombu wynosi {a*h}')
 elif inp == "9":
  e = float(input("e = "))
  f = float(input("f = "))
  print(f'przekatne rombu wynosza {(e*f)/2}')
elif inp == '2':
 print("""
 1 - obwod kwadratu
 2 - obwod prostokatu
 3 - obwod rownolegloboku
 4 - obwod trapezu
 5 - obwod trojkata
 6 - obwod trojkata rownobocznego
 7 - obwod kola
 8 - obwod rombu""")
 inp = input()
 if inp == "1":
  a = float(input("a = "))
  print(f'obwod kwadratu wynosi {4*a}')
 elif inp == "2":
  a = float(input("a = "))
  b = float(input("b = "))
  print(f'obwod prostokatu wynosi {2*a + 2*b}')
 elif inp == "3":
  a = float(input("a = "))
  b = float(input("b = "))
  print(f'obwod rownolegloboku wynosi {2*a + 2*b}')
 elif inp == "4":
  a = float(input("a = "))
  b = float(input("b = "))
  c = float(input("c = "))
  d = float(input("d = "))
  print(f'obwod trapezu wynosi {a+b+c+d}')
 elif inp == "5":
  a = float(input("a = "))
  b = float(input("b = "))
  c = float(input("c = "))
  print(f'obwod trojkota wynosi {a + b + c}')
 elif inp == "6":
  a = float(input("a = "))
  print(f'obwod trojkata rownobocznego wynosi {3*a}')
 elif inp == "7":
  r = float(input("r = "))
  print(f'obwod kola wynosi {2 * math.pi * r}')
 if inp == "8":
  a = float(input("a = "))
  print(f'obwod rombu wynosi {4*a}')
elif inp == '3':
 print("""
 1 - objetosc szescianu
 b - objetosc prostopadloscianu
 c - objetosc graniastoslupa
 d - objetosc ostroslupa
 e - objetosc walca
 f - objetosc stozka
 g - objetosc kuli
 """)
 inp = input()
 if inp == "1":
  a = float(input("a = "))
  print(f'objetosc szescianu wynosi {a**3}')
 elif inp == "b":
  a = float(input("a = "))
  b = float(input("b = "))
  c = float(input("c = "))
  print(f'objetosc szescianu wynosi {a*b*c}')
 elif inp == "c":
  pp = float(input("pp = "))
  h = float(input("h = "))
  print(f'objetosc graniastoslupa wynosi {pp*h}')
 elif inp == "d":
  pp = float(input("pp = "))
  h = float(input("h = "))
  print(f'objetosc ostroslupa wynosi {(pp*h)/3}')
 elif inp == "e":
  r = float(input("r = "))
  h = float(input("h = "))
  print(f'objetosc walca wynosi {math.pi * r**2 * h}')
 elif inp == "f":
  r = float(input("r = "))
  h = float(input("h = "))
  print(f'objetosc stozka wynosi {(math.pi * r**2 * h)/3}')
 elif inp == "g":
  r = float(input("r = "))
  print(f'objetosc kuli wynosi {(math.pi * r**3) * (4/3) }')
elif inp == '4':
 print("""
 a - pole powierzchni szescianu
 b - pole powierzchni prostopadloscianu
 c - pole powierzchni graniastoslupa
 d - pole powierzchni ostroslupa
 e - pole powierzchni walca
 f - pole powierzchni stozka
 g - pole powierzchni kuli""")
 inp = input()
 if inp == "a":
  a = float(input("a = "))
  print(f'pole powierzchni szescianu wynosi {6 * a**2}')
 elif inp == "b":
  ab = float(input("ab = "))
  ac = float(input("ac = "))
  bc = float(input("bc = "))
  print(f'pole powierzchni prostopadloscianu wynosi {2 * ab + 2 * ac + 2 * bc}')
 elif inp == "c":
  pb = float(input("pb = "))
  pp = float(input("pp = "))
  print(f'pole powierzchni graniastoslupa wynosi {2 * pp + pb}')
 elif inp == "d":
  pb = float(input("pb = "))
  pp = float(input("pp = "))
  print(f'pole powierzchni ostroslupa wynosi {pp + pb}')
 elif inp == "e":
  r = float(input("r = "))
  h = float(input("h = "))
  print(f'pole powierzchni walca wynosi {2*math.pi * r**2 + 2 * math.pi * r * h}')
 elif inp == "f":
  r = float(input("r = "))
  l = float(input("l = "))
  print(f'pole powierzchni stozka wynosi {math.pi * r**2 + math.pi*r*l}')
 elif inp == "g":
  r = float(input("r = "))
  print(f'pole powierzchni kuli wynosi {4 * math.pi * r**2}')
elif inp == '5':
 print("""
 a - wysokosc trojkata rownobocznego
 b - przekatna kwadratu
 c - pitagoras""")
 inp = input()
 if inp == "a":
  a = float(input("a = "))
  print(f'wysokosc trojkata rownobocznego wynosi {(a * math.sqrt(3)/2)}')
 elif inp == "b":
  a = float(input("a = "))
  print(f'przekatna kwadratu to {a * math.sqrt(2)}')
 elif inp == "c":
  a = float(input("a = "))
  b = float(input("b = "))
  c = float(input("c = "))
  print(f'dlugosc przeciwprostokatnej wynosi {a**2 + b**2}')
