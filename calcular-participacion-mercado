import numpy as np

# Definir la matriz de transición
transicion = np.array([
    [0.88, 0.12],
    [0.15, 0.85]
])

# Definir el vector de estado inicial
estado_inicial = np.array([0.25, 0.75])

# Calcular la participación de mercado en 2 años
estado_2_anios = np.dot(transicion, estado_inicial)
participacion_2_anios = estado_2_anios[0] / np.sum(estado_2_anios)

# Calcular la participación de mercado en 4 años
estado_4_anios = np.dot(transicion, estado_2_anios)
participacion_4_anios = estado_4_anios[0] / np.sum(estado_4_anios)

# Imprimir los resultados
print(f"Participación de mercado en 2 años: {participacion_2_anios:.2%}")
print(f"Participación de mercado en 4 años: {participacion_4_anios:.2%}")
