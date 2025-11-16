# Caixa-Branca-Parte-1-

# Notação de Grafo de Fluxo

## Grafo de Fluxo - conectarBD()
<img width="2248" height="2540" alt="image" src="https://github.com/user-attachments/assets/ee93a48f-9f63-4e82-a817-696e8ed5a4a7" />

## Grafo de Fluxo - verificarUsuario()
<img width="2584" height="3296" alt="image" src="https://github.com/user-attachments/assets/dc7e8ce4-3aa1-49cf-92ea-a91fec595bfa" />



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
