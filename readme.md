1. O Objetivo deste código se trata criar um sistema que fila hospitalar, onde podemos gerenciar os pacientes.
Deste modo o sitema permite:
    A. Organizar os pacientes por ordem de prioridade;
    B. Marcar ou desmarcar os atendimentos;
    C. Visualizar a lista de atendimentos;
    D. Ler atendimentos por aquivos de extensão ".txt", que sigam o seguinte modelo:
        nome,idade,sexo,cor_de_atendimento 
        Ana,22,F,verde
        Bruno,35,M,azul

2. Os atendimentos seguem a seguintes cores tendo as respectivas definições:
    A. AZUL 1 - Casos simples, sem gravidade e pouca prioridade.
    B. VERDE 2 - Casos de menor gravidade, detem certa prioridade.
    C. AMARELO 3 - Atendimento grave, exige uma maior atenção e menor tempo de resposta.
    D. LARANJA 4 - Atendimento grave, exindo atendimento urgente.
    E. VERMELHO 5 - Atendimento imediato, respota imediata se faz necessária.