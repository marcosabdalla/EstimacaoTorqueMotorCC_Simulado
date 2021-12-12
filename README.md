# Estimacao Torque MotorCC Simulado

Este código mostra como utilizar uma Rede Neural Atificial para estimar o valor do toque desenvolvido por um motor CC de excitação independente. Os dados foram montados simulando um vetor de tensão de terminal de 127V com um erro aleatório de +- 1V. A corrente de armadura foi aumentada de 0 a 5 amperes adicionado um erro de medição aleatório de +-0.1. A velocidade assim como a corrente foi criada a partir de um vetor de 0 a 188.4 rad/s com uma variação de +-1. A reistência de armadura foi retirada de uma máquina real e vale 0.1 Ohms. 

<img src="https://render.githubusercontent.com/render/math?math=T = \frac{Ea.Ia}{\omega}">
