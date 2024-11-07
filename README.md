 # Importações
import turtle

# Criação da janela
janela = turtle.Screen()
janela.title("Leão")
janela.bgcolor("yellow")

# Criação do corpo do leão
corpo = turtle.Turtle()
corpo.shape("circle")
corpo.color("brown")
corpo.penup()
corpo.goto(0, 0)
corpo.pendown()
corpo.circle(50)

# Criação da cabeça do leão
cabeca = turtle.Turtle()
cabeca.shape("circle")
cabeca.color("brown")
cabeca.penup()
cabeca.goto(0, 50)
cabeca.pendown()
cabeca.circle(25)

# Criação dos olhos do leão
olho_esquerdo = turtle.Turtle()
olho_esquerdo.shape("circle")
olho_esquerdo.color("black")
olho_esquerdo.penup()
olho_esquerdo.goto(-10, 60)
olho_esquerdo.pendown()
olho_esquerdo.circle(5)

olho_direito = turtle.Turtle()
olho_direito.shape("circle")
olho_direito.color("black")
olho_direito.penup()
olho_direito.goto(10, 60)
olho_direito.pendown()
olho_direito.circle(5)

# Criação do nariz do leão
nariz = turtle.Turtle()
nariz.shape("triangle")
nariz.color("black")
nariz.penup()
nariz.goto(0, 55)
nariz.pendown()

# Criação da boca do leão
boca = turtle.Turtle()
boca.shape("arc")
boca.color("black")
boca.penup()
boca.goto(-20, 45)
boca.pendown()
boca.setheading(270)
boca.circle(20, 180)

# Criação da juba do leão
juba = turtle.Turtle()
juba.shape("circle")
juba.color("yellow")
juba.penup()
juba.goto(0, 70)
juba.pendown()
juba.circle(70)

# Criação da cauda do leão
cauda = turtle.Turtle()
cauda.shape("line")
cauda.color("brown")
cauda.penup()
cauda.goto(0, 0)
cauda.pendown()
cauda.setheading(270)
cauda.forward(100)

# Exibição do desenho
janela.mainloop()
