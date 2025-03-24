# Diagnóstico de Asma com Lógica Fuzzy

Este projeto implementa um sistema baseado em **Lógica Fuzzy** para diagnosticar a gravidade da asma com base em três variáveis: **frequência de crises**, **uso de SABA** e **débito expiratório**. O objetivo é classificar a gravidade da asma como **moderada**, **aguda grave** ou **risco de vida**.

## Objetivo

A asma é uma doença respiratória crônica que pode variar de intensidade ao longo do tempo. Este modelo utiliza **Lógica Fuzzy** para analisar diferentes fatores e determinar a gravidade da condição do paciente, auxiliando na tomada de decisões médicas.


## Tecnologias Utilizadas

- **Python**
- **Scikit-Fuzzy** (para modelagem do sistema Fuzzy)
- **Matplotlib** (para visualização dos conjuntos fuzzy)

## Como funciona o Modelo Fuzzy

O modelo é baseado em três variáveis de entrada:

1. **Crises** (frequência das crises asmáticas)
2. **SABA** (uso de broncodilatadores de resgate)
3. **Débito Expiratório** (capacidade respiratória)

Essas variáveis são processadas utilizando **funções de pertinência fuzzy**, que classificam os valores de entrada em diferentes categorias. A saída do modelo é a **gravidade da asma**, classificada como:

- **Moderada**
- **Aguda grave**
- **Risco de vida**

O sistema fuzzy utiliza regras definidas para combinar os valores de entrada e gerar um diagnóstico preciso.
