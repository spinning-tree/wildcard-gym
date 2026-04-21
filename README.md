# Wildcard Pro: Generador de Entrenamiento para Redes

## Descripción
Aplicación web estática diseñada para la práctica de cálculo de máscaras wildcard en protocolos de enrutamiento como EIGRP y OSPF. El sistema genera ejercicios de forma procedural, eliminando la dependencia de una base de datos de preguntas estáticas o llamadas a APIs externas.

## Funcionalidades
* Generación Procedural: Algoritmos locales que calculan IPs, máscaras de subred (CIDR) y sus correspondientes wildcards en tiempo real.
* Variedad de Octetos: Los ejercicios no se limitan al cuarto octeto; el sistema genera casos que afectan a los octetos primero, segundo y tercero para practicar agregación de rutas y bloques de red mayores.
* Modos de Ejercicio:
    * Conversión directa de máscara de subred a wildcard.
    * Identificación de wildcard para hosts específicos (/32).
    * Cálculo de bloques de red y rangos de subred.
    * Sintaxis completa de comandos de configuración en CLI de Cisco.

## Detalles Técnicos
* Framework: React 18.
* Lógica de Red: Implementada mediante operaciones de bits (bitwise operations) en JavaScript para asegurar precisión técnica en los cálculos de red.
* Estilos: Tailwind CSS con diseño optimizado para legibilidad de datos técnicos.
* Iconografía: Lucide React.

## Instalación y Uso
Al ser una aplicación basada en componentes funcionales de React, puede ser integrada en cualquier proyecto existente o ejecutada como una Single Page Application (SPA).


## Objetivo Pedagógico
Fomentar la agilidad mental en la configuración de protocolos de enrutamiento dinámico, reforzando el concepto de la wildcard como el inverso binario de la máscara de subred y su aplicación práctica en la activación de interfaces.
