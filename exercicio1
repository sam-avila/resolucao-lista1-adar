```
#Lista de exercícios 5.6
#1 Execute as seguintes expressões no R mostrando os resultados obtidos
1+1
100:00
5-+1
(3/5)*100
2*1
4-1
6/4

#2 Utilize uma expressão para cada item
#a) escolha um número e some 3 a ele 
5+3
#b) multiplique o resultado por 2
8*2
#C) subitraia 10 da resposta
16-10
#d) divida oque foi obtidoc por 4
6/4

#3) Calcule 
sqrt (16)
16^(0.5)^(3)
(16^(0.5))^(3)
4^(3/2)

#4) teste as expressões log10(1000), log(1000),exp(log(1000)).Depois testar a 
#expressão log2(64). verifique se você entendeu as diferentes funções
#logarítimicas.

log10(1000)
#essa função calcula o logaritimo de 1000 na base 10
log(1000)
#essa função calcula o logaritimo natural de 1000 na base exp=2.718
exp(log(1000))
#essa função aplica a função exponencial à função logarítimica natural de 
#1000.
log2(64)
#essa função calcula o logaritimo de 64 na base 2


#5) defina as variáveis abaixo tomando cuidado ao nomear as variáveis,
#conforme visto em sala de aula.
#Mostre os valorespara as seguintes constantes:

luz<-2.998*10^8
CE<-1.602*10^-19
PV<-8.85*10^-12
CP<-6.662*10^-12
CSB<-5.67*10^-8
CA<-6.022*10^23
CGAS<-287.04
CGIV<-461.5
CNPT<-1.2754
PNMM_PA<-1013.25
TNMM_PA<-288.15
CL<-2.501*10^6
CLF<-0.334*10^6
MMA<-18.016
PMAR<-28.96
RTERRA<-6.37*10^6
VAT<-7.26*10^-5

#6) Como você pode fazer para que a constante de (pi) seja mostrada com 20
#digitos? 
#como voltar a trabalhar com 7 digitos novamente?
#mostre número neperiano com 7 digitos

pi
options(digits = 20)
pi
options(digits = 7)
pi
exp(1)

#7)Determine a temperatura de bulbo úmido(Tw) usando a expressão empirica 
#stull, 2011 abaixo 

TEMP<-20
UR<-70
TEMP * atan(0.151977*sqrt(UR+8.313659)) + atan(TEMP+UR) -
atan(UR - 1.676331) + 0.00391838 * UR^(3/2) * atan(0.023101*UR)-4.686035

#RESP Tw = 16.28012 

#8) Determine os valores de umidade de solo: 
SI<-16.29
CL<-49.25
Dd<-1.25
Me<-25

X14<- -1.05501+0.650857*SI
X15<- -2.07588+0.0423954*CL
X16<- -6.03402+4.80572*Dd
X17<- -2.18409+8.84963*Me/100
Z9<- 0.175202+1.18513*X17-0.0996042*(X17)^2+0.327915*X16-0.758657*(X16)^2
Z10<-0.929344*Z9+0.132519*X14
KPA10<- 0.339255+0.112526*Z10
Z11<- 0.191452+1.25652*(X17)^2+0.393814*X16+0.152095*X17*X16
KPA33<-0.28951+0.103815*Z11
Z13<- 0.235080+0.33033*X15-0.191838*X15^2+0.0543679*X15^3+0.977685*
 X17+0.304174*X15*X16-0.218857*X17^2-0.164373*X15*X17^2+0.0415057*
X17^3+0.373361*X16+0.0811861*X17*X16-0.0768087*X15*X17*X16

KPA1500<- 0.224008+0.0862945*Z13
KPA1500
#RESULTADO 0.2461308

#9 Arredonde para 2 casas decimais os resultados da questão 8 
round(KPA1500,2)
#RESULTADO 0.25

#10)ALTERAÇÕES NO SCRIPT
```
