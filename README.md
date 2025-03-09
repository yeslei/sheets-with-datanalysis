# Funções Básicas do Google Sheets

## 📈 Funções Matemáticas e Estatísticas

=SOMA(A1:A10) → Soma os valores no intervalo.

=MÉDIA(A1:A10) → Calcula a média dos valores.

=MÁXIMO(A1:A10) → Retorna o maior valor do intervalo.

=MÍNIMO(A1:A10) → Retorna o menor valor do intervalo.

=CONT.NÚM(A1:A10) → Conta apenas células com números.

=CONT.VALORES(A1:A10) → Conta todas as células não vazias.

## 🔠 Funções de Texto

=CONCATENAR(A1, B1) → Junta textos de duas células.

=TEXTO(A1, "DD/MM/AAAA") → Formata um número/data para texto.

=ESQUERDA(A1, 3) → Retorna os 3 primeiros caracteres do texto.

=DIREITA(A1, 2) → Retorna os 2 últimos caracteres do texto.

=EXT.TEXTO(A1, 2, 3) → Retorna 3 caracteres a partir da posição 2.

## 🔍 Funções Lógicas

=SE(A1>10, "Maior que 10", "Menor ou igual a 10") → Condição simples.

=SE(E(A1>5, B1<20), "Verdadeiro", "Falso") → Testa múltiplas condições.

=SE(OU(A1="Sim", B1=100), "Aprovado", "Reprovado") → Condição com OU.

## 🔄 Funções de Pesquisa e Referência

=PROCV(1001, A2:C10, 2, FALSO) → Procura "1001" na coluna A e retorna o valor da 2ª coluna.

=ÍNDICE(A2:C10, 2, 3) → Retorna o valor da linha 2 e coluna 3.

=CORRESP(50, A2:A10, 0) → Retorna a posição do valor 50 na coluna A.

## ⏳ Funções de Data e Hora

=HOJE() → Retorna a data atual.

=AGORA() → Retorna a data e hora atual.

=DIATRABALHOTOTAL(A1, B1) → Calcula dias úteis entre duas datas.

## 📚 Conceitos Adicionais

### Interpolação

- A interpolação é um método matemático usado para estimar valores dentro de um intervalo de dados conhecidos. No Google Sheets, pode ser realizada usando funções como =TENDÊNCIA() e =PROJ.LIN(), que ajudam a prever valores com base em padrões existentes.

### Variância

- A variância mede a dispersão de um conjunto de dados em relação à média. No Google Sheets, pode ser calculada usando =VAR.P(A1:A10) para a população inteira ou =VAR.A(A1:A10) para uma amostra.

### Desvio Padrão

- O desvio padrão mede o grau de dispersão dos valores em relação à média. No Google Sheets, pode ser calculado usando:

=DESVPAD.P(A1:A10) para a população inteira.

=DESVPAD.A(A1:A10) para uma amostra.

### Média Móvel

- A média móvel é uma técnica estatística usada para suavizar variações em dados ao longo do tempo. Ela ajuda a identificar tendências e padrões eliminando ruídos e flutuações momentâneas.
