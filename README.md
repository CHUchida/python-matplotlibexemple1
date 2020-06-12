# python-matplotlibexemple1

import matplotlib.pyplot as plt

mes=[1,2,3,4,5,6]
vendas=[100,200,300,45,59,600]

plt.xlabel('meses')
plt.ylabel('vendas')

plt.plot(mes,vendas)
plt.show()
