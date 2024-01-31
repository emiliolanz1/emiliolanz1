# Gráfico sin datos con líneas

import matplotlib.pyplot as plt

# Definimos el rango de los ejes
x_min = 0
x_max = 10
y_min = 0
y_max = 100

# Creamos las líneas
plt.plot([0, 5], [0, 100], color="red")
plt.plot([5, 10], [100, 0], color="blue")

# Creamos el título
plt.title("Gráfico sin datos con líneas")

# Mostramos el gráfico
plt.show()
