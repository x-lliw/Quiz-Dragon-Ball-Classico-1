print("Seja muito bem-vindo ao quiz do Will!")

anwser_user = input("Quer começar? (S/N): ").upper()

if anwser_user != "S":
    quit()

score = 0

print("\nComeçando...\n")

print("Quem foi a primeira pessoa que Goku conheceu em Dragon Ball clássico?")
print("(A) Bulma")
print("(B) Kuririn")
print("(C) Mestre Kame")
print("(D) Vegeta")
anwser_1 = input("Resposta: ").upper()

if anwser_1 == "A":
    print("Correto!")
    score += 2
else:
    print("Incorreto!")

print("\nQual a técnica mais conhecida do Goku?")
print("(A) Kamehameha")
print("(B) Taiyoken")
print("(C) Hakai")
print("(D) Cura")
anwser_1 = input("Resposta: ").upper()

if anwser_1 == "A":
    print("Correto!")
    score += 2
else:
    print("Incorreto!")

print("\nQual foi o primeiro rival do Goku na série clássica?")
print("(A) Yancha")
print("(B) Gohan")
print("(C) Saitama")
print("(D) Kuririn")
anwser_1 = input("Resposta: ").upper()

if anwser_1 == "D":
    print("Correto!")
    score += 2
else:
    print("Incorreto!")

print("\nQual a fraqueza do Vegeta?")
print("(A) Não tem fraqueza")
print("(B) Seu orgulho Sayajin")
print("(C) Sua raiva")
print("(D) Cortar o cabelo")
anwser_1 = input("Resposta: ").upper()

if anwser_1 == "B":
    print("Correto!")
    score += 2
else:
    print("Incorreto!")

print("\nComo se chama o cargo de Deus da Terra em Dragon Ball?")
print("(A) Master")
print("(B) Não tem esse cargo")
print("(C) Deus")
print("(D) Kamisama")
anwser_1 = input("Resposta: ").upper()

if anwser_1 == "D":
    print("Correto!")
    score += 2
else:
    print("Incorreto!")

print(f"\nQuiz acabou! Pontuação final: {score}/10")
