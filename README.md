# Modulo-6
Modulo 6 do curso Mentorama

import matplotlib.pyplot as plt
import pandas as pd
import numpy as np

df = pd.read_csv("titanic.csv")

df.head()

passengerid = ID do passageiro;
survived = 1 se sobreviveu, 0 caso contrário.
pclass = Tipo de classe de passagem. Possui 3 valore sendo 1 a melhor classe e 3 a pior classe.
name = Nome do passageiro
sex = sexo do passageiro (M e F).
age = Idade do passageiro na data do naufrágio.
sibsp = Número de irmãos / cônjuges a bordo.
parch = Número de pais / filhos a bordo.
ticket = Código do ticket.
fare = Valor da passagem.
cabin = Código da Cabine.
embarked = Local de embarque.
