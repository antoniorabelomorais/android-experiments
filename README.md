# Kotlin Test — Termux / Android Dev Stack

Este repositório contém um teste simples para validar o funcionamento
do Kotlin + JDK no Termux, dentro do ambiente Android.

Arquivo: `test.kt`
Descrição: Código Kotlin simples que imprime "Kotlin OK!".
Finalidade: Confirmar integração do `kotlinc` + `java` sem erros críticos,
mesmo com o warning de `jansi`.

Como executar:
1. Compilar:
   kotlinc test.kt -include-runtime -d test.jar
2. Executar:
   java -jar test.jar

deixei um test.jar já compilado usando o jdk 17 no Termux 0.119.0-beta.3 em um moto g34 5G
