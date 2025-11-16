# Caixa-Branca-Parte-1-

# Notação de Grafo de Fluxo

## Grafo de Fluxo - conectarBD()
<img width="2248" height="2540" alt="image" src="https://github.com/user-attachments/assets/b221e267-d4d8-48c8-a369-74763c685a37" />

## Grafo de Fluxo - verificarUsuario()
<img width="2584" height="3296" alt="image" src="https://github.com/user-attachments/assets/4f91c6cb-8dda-47fa-8fca-f4818b7071cd" />



## NOTAÇÃO GRAFO DE FLUXO - Método verificarUsuario()

Caminho Básico 1 – Resultado encontrado (true)
N1 → N2 → N3 → N4(true) → N5 → N8 → N9

Caminho Básico 2 – Nenhum resultado (false)
N1 → N2 → N3 → N4(false) → N6 → N8 → N9

Caminho Básico 3 – Exceção (catch)
N1 → N2 → N3 → N7 → N8 → N9

## NOTAÇÃO GRAFO DE FLUXO - Método conectarBD()

Caminho Básico 1 - Execução Normal (Sem exceção)
N1 → N2 → N3 → N4 → N6

Caminho Básico 2 - Exceção do Try
N1 → N2 → N3 → N5 → N6

# Complexidade Ciclomática

## conectarBD() - 6 nós e 6 arestas
M = E - N + 2
M = 6 - 6 + 2
M = 2

## verificarUsuario() - 9 nós e 10 arestas
M = E – N + 2P
M = 10 – 9 + 2(1)
M = 10 – 9 + 2
M = 3
