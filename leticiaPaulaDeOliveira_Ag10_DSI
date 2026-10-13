# Importa as cores e o recurso para restaurar o estilo do terminal
from colorama import Fore, Style

# Lista com os níveis do reservatório
niveis = [
    "Nivel 1 - Muito baixo (critico)",
    "Nivel 2 - Baixo",
    "Nivel 3 - Medio",
    "Nivel 4 - Alto",
    "Nivel 5 - Muito alto (alerta)"
]

# Funcao para definir a cor de cada nivel
def definir_cor(nivel):

    # Se o nivel for 1, retorna a cor vermelha
    if nivel == 1:
        return Fore.RED

    # Se o nivel for 2, retorna a cor amarela
    elif nivel == 2:
        return Fore.YELLOW

    # Se o nivel for 3, retorna a cor verde
    elif nivel == 3:
        return Fore.GREEN

    # Se o nivel for 4, retorna a cor ciano
    elif nivel == 4:
        return Fore.CYAN

    # Se o nivel for 5, retorna a cor azul
    elif nivel == 5:
        return Fore.BLUE


# Percorre todos os elementos da lista
for i in range(len(niveis)):

    # Define a cor de acordo com o nivel atual
    cor = definir_cor(i + 1)

    # Exibe a mensagem colorida e restaura o estilo do terminal
    print(cor + niveis[i] + Style.RESET_ALL)