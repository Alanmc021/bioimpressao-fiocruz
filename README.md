Este código usa o modo absoluto de coordenadas (G90) para definir as coordenadas a partir do ponto zero da impressora 3D. O primeiro comando (G1) move a impressora para o ponto inicial (X=50, Y=50) com uma taxa de alimentação de 1000 mm/min.

O segundo comando (G2) faz um movimento circular no sentido horário, com um raio de 25 mm (I25) e centro em X=75 e Y=50 (J0). A taxa de alimentação é de 500 mm/min.

O terceiro comando (G1) move a impressora de volta para o ponto inicial com uma taxa de alimentação de 1000 mm/min.

Note que os comandos G1 e G2 utilizam as coordenadas X e Y para definir a posição da impressora na superfície de impressão, e os comandos I e J para definir o centro do movimento circular em relação às coordenadas X e Y. O comando F é utilizado para definir a taxa de alimentação em mm/min.