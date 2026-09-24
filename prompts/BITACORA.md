# Bitacora de prompts
 
Laboratorio 06: Fundamentos de Ingenieria de Prompts.
 
Herramienta de IA usada: Claude
 
## Ejercicio 2: Tokens y ventana de contexto

  Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. | 34 | 7 |
| The students program in Java. | 29 | 6 |
| desafortunadamente |18 | 4 |

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 | 100%|BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5 |65.3% |BiblioTec, LibroYa, BiblioTec, PrestaLibro, BiblioTec |
| 1 |44.5% |BiblioTec, PrestaLibro, LibroYa, LectoGo, BiblioTec |
| 1.8 |32.2% |LibroYa, PaginaLibre, BiblioTec, NubeDeTinta, PrestaLibro |

## Ejercicio 4: Prompt vago vs estructurado

 | Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema |Sí |Sí |
| Menciona a los usuarios principales |No |Sí|
| Tiene exactamente 3 funcionalidades |No |Sí |
| Esta en 3 parrafos |No |Sí |
| Lo usaria en un informe real |No |Sí   |

## Ejercicio 5: Anatomia de un prompt

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol |Desarrollador de Java |
| Instruccion |Crea un programa en Java usando una clase Producto con los atributos codigo, nombre, precio y stock |
| Contexto |para gestionar los productos de una tienda |
| Ejemplo |Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). |
| Formato |Explica primero la estructura de la clase y luego presenta el codigo Java |
 
## Ejercicio 6: Del prompt basico al profesional
