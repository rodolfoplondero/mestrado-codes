# Mestrado-codes

Esse espaço está sendo utilizado para organizar os cálculos e algoritmos utilizados ao longo do mestrado.

---

- [Mestrado-codes](#mestrado-codes)
  - [Plot dos resultados](#plot-dos-resultados)
  - [Cálculos](#cálculos)
  - [Propriedades do Ar](#propriedades-do-ar)
  - [Acoplamento Fluent-Maxwell](#acoplamento-fluent-maxwell)

---

## [Plot dos resultados](https://github.com/rodolfoplondero/mestrado-codes/tree/main/plot-results)

Código em Python para plotar os resultados obtidos do [Ansys Fluent](https://www.ansys.com/products/fluids/ansys-fluent).

## [Cálculos](https://github.com/rodolfoplondero/mestrado-codes/tree/main/calcs)

Calculos gerais utilizados para as simulações

## [Propriedades do Ar](https://github.com/rodolfoplondero/mestrado-codes/tree/main/air-properties)

Essa pasta contém os códigos utilizados para realizar o plot das seguintes propriedades do ar:

- Densidade
- Calor Específico
- Viscosidade
- Condutividade Térmica
- Condutividade Elétrica

*Para visualizar, acesse o arquivo [Propriedades do Ar/air-properties.ipynb](https://github.com/rodolfoplondero/Mestrado/blob/main/Codigos/air-properties/air-properties.ipynb)*

## [Acoplamento Fluent-Maxwell](https://github.com/rodolfoplondero/mestrado-codes/tree/main/fluent-maxwell-coupling)

Projeto em [C](https://pt.wikipedia.org/wiki/C_%28linguagem_de_programa%C3%A7%C3%A3o%29) para realizar o acoplamento entre Fluent-Maxwell utilizando corrente alternada (CA). Em resumo, é uma UDF (do inglês, *User-Defined Function*) que calcula e atualiza o arquivo de excitações que o Maxwell lê cada vez que é chamado pelo Fluent.
