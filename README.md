# Desenvolva-um-programa-que-utiliza-o-nome-de-um-aluno-duas-notas-e-a-quantidade-de-faltas-que-ele-t
algoritmo "falta dos alunos"

var

notas: vetor [1..35]de real

media: real

i: inteiro

aluno: inteiro

inicio

// Seção de Comandos

media <- 0

Para i De 1 Ate 35 Passo 1 Faca

Escreva ("Digite a nota do 1o bim: ")

Leia(notas)

media <- media + notas

FimPara

media <- media/5

Para i De 1 Ate 35 Passo 1 Faca

Escreval("Nota " ,i, "=", notas)

FimPara

Escreva("Média: ", media)

fimalgoritmo

algoritmo "falta dos alunos"
INICIO
LITERAL:NOME
REAL:N1, N2, N3, MEDIA
ESCREVAL("SISTEMA DE MÉDIAS")
ESCREVA("DIGITE A PRIMEIRA NOTA: ")
LEIA(N1)
ESCREVA("DIGITE A SEGUNDA NOTA: ")
LEIA(N2)
ESCREVA("DIGITE A TERCERIA NOTA: ")
LEIA(N3)
MEDIA <- (N1 + N2 + N3) / 3
SE MEDIA >= 7 ENTAO
 ESCREVAL("ALUNO APROVADO!")
SENAO
 SE MEDIA <= 5 ENTAO
 ESCREVAL("ALUNO REPROVADO!")
 SENAO
 ESCREVAL("ALUNO EM RECUPERAÇÃO...")
 FIMSE
FIMSE
FIM


algoritmo " exercício 12 - quinta aula prática "
var nome, sexo: caractere
n1, n2, n3, media, med_h_soma, med_m_soma: real
faltas,num_h_rf,num_m_rf,num_h_rm,num_m_rm: inteiro
total_h,total_m : inteiro
inicio
num_h_rf <- 0
num_m_rf <- 0
num_h_rm <- 0
num_m_rm <- 0
total_h <- 0
total_m <-0
med_h_soma <- 0.0
med_m_soma <- 0
repita
escreva ("Entre com o nome do aluno(a) " )
escreva ("(para finalizar a execução digite a palavra ‘fim’): ")
leia (nome)
se (nome<>"fim") entao
repita
escreva ("Entre com o sexo (M =Masculino e F=Feminino): ")
leia (sexo)
ate (sexo="m" ou sexo="f")

fimse
fimalgoritmo


algoritmo " exercício 12 - quinta aula prática "
var nome, sexo: caractere
n1, n2, n3, media, med_h_soma, med_m_soma: real
faltas,num_h_rf,num_m_rf,num_h_rm,num_m_rm: inteiro
total_h,total_m : inteiro
inicio
num_h_rf <- 0
num_m_rf <- 0
num_h_rm <- 0
num_m_rm <- 0
total_h <- 0
total_m <-0
med_h_soma <- 0.0
med_m_soma <- 0
repita
escreva ("Entre com o nome do aluno(a) " )
escreva ("(para finalizar a execução digite a palavra ‘fim’): ")
leia (nome)
se (nome<>"fim") entao
repita
escreva ("Entre com o sexo (M =Masculino e F=Feminino): ")
leia (sexo)
ate (sexo="m" ou sexo="f")

fimse
fimalgoritmo
