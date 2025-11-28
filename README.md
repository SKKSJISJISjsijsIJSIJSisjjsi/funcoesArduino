# funcoesmatematicas_arduino

📘 Exercícios de Arduino – Funções Matemáticas, Serial e Manipulação de Texto

Este repositório contém quatro exercícios feitos em Arduino abordando leitura analógica, funções matemáticas, manipulação de texto e controle de brilho com seno.
Cada exercício inclui descrição, objetivo e código base.

✅ Exercício 1 – Cálculo de média e arredondamento
🎯 Objetivo

Ler valores de um potenciômetro usando analogRead().

Calcular a média aritmética de três leituras.

Calcular a raiz quadrada da média.

Exibir os resultados com arredondamento no Serial Monitor.

📌 Pontos trabalhados

Entrada analógica (analogRead)

Funções matemáticas: sqrt(), round(), ceil()

Saída pelo Serial Monitor

✅ Exercício 2 – Movimento de LED com funções trigonométricas
🎯 Objetivo

Criar um efeito de "respiração" em um LED, variando o brilho suavemente usando a função seno.

📌 Pontos trabalhados

Saída PWM (analogWrite)

Função sin() para movimento suave

Conversão de valores: -1 a 1 → 0 a 255

✅ Exercício 3 – Conversor de ângulos
🎯 Objetivo

Ler valores X e Y digitados pelo usuário via Serial Monitor e calcular o ângulo de inclinação usando atan2().

📌 Pontos trabalhados

Entrada pelo Serial (Serial.parseFloat)

Cálculo com atan2()

Conversão de radianos para graus

✅ Exercício 4 – Manipulação de texto no Serial Monitor
🎯 Objetivo

Receber uma palavra digitada pelo usuário e retornar:

Quantos caracteres foram digitados

A palavra toda em letras maiúsculas

Uma saudação personalizada: “Olá, PALAVRA!”

📌 Pontos trabalhados

Leitura de strings pelo Serial (readBytesUntil)

Manipulação de caracteres (toupper)

Uso de strlen, strcat e arrays de char
