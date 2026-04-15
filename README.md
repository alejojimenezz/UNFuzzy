
# UNFuzzy

<div align="center">
  <img src="./bmp/UNFicon.png" alt="Texto alternativo" />
</div>

Fuzzy Logic Systems - FSL (Fuzzy controllers), and networks of FSLs

UNFuzzy es un software para diseño de Sistemas de Lógica Difusa (Controladores difusos). 
UNFuzzyNetwork permite el diseño de Redes de Sistemas de Lógica Difusa.

Para compilarlo se utiliza codeblocks y wxWidgets

- [UNFuzzy](#unfuzzy)
  - [Ejecución del programa](#ejecución-del-programa)
  - [Opciones - Ventana inicial](#opciones---ventana-inicial)
    - [Barra superior](#barra-superior)
    - [Sistema](#sistema)
    - [Sin ubicar](#sin-ubicar)


## Ejecución del programa

Desde el [Release de GitHub](https://github.com/ogduartev/UNFuzzy/releases/tag/v3.0.0) se puede descargar el archivo comprimido de los binarios, o tambien descargando el repositorio; para cualquier opción, se encontrarán los ejecutables en la ruta "./UNFuzzy/win/". Si se descarga el repositorio, en la ruta mencionada "./UNFuzzy/win/", se encontrará un comprimido; al desempaquetarlo, se encontrarán igualmente los archivos ejecutables.

## Opciones - Ventana inicial

### Barra superior

| Ícono                             | Nombre   | Descripción                                                            |
| --------------------------------- | -------- | ---------------------------------------------------------------------- |
| ![iconNuevo](bmp/Nuevo.bmp)       | Nuevo    | Inicia un nuevo archivo de un sistema con valores predeterminados      |
| ![iconLeer](bmp/Leer.bmp)         | Leer     | Abre un sistema previamente guardado                                   |
| ![iconGuardar](bmp/Guardar.bmp)   | Guardar  | Guarda el sistema del archivo abierto                                  |
| ![iconDescribe](bmp/Describe.bmp) | Describe | Permite asignar nombre y descripción al sistema del archivo actual     |
| ![iconEntrenar](bmp/Entrenar.bmp) | Entrenar | Ventana para asignar pares de datos Entrada-Salida                     |
| ![iconFuncion](bmp/Funcion.bmp)   | Funcion  | Ventana para graficar la relación Entrada-Salida del sistema           |
| ![iconCalcular](bmp/Calcular.bmp) | Calcular |                                                                        |
| ![iconPaso](bmp/Paso.bmp)         | Paso     |                                                                        |
| ![iconCodigo](bmp/Codigo.bmp)     | Codigo   | Genera el código fuente del sistema en lenguaje C++ (`*.cpp`)          |
| ![iconTabla](bmp/Tabla.bmp)       | Tabla    | Genera un archivo `.csv` con los datos del sistema del archivo abierto |
| ![iconIdioma](bmp/Idioma.bmp)     | Idioma   | Cambiar idioma entre español e inglés                                  |
| ![iconAcerca](bmp/Acerca.bmp)     | Acerca   | Créditos del software UNFuzzy                                          |

### Sistema
![iconEntradas](bmp/Entradas.bmp)
![iconMotor](bmp/Motor.bmp)
![iconReglas](bmp/Reglas.bmp)
![iconSalidas](bmp/Salidas.bmp)

### Sin ubicar
![iconTMP](bmp/TMP.bmp)
![iconadicionaCapa](bmp/adicionaCapa.bmp)
![iconeliminaCapa](bmp/eliminaCapa.bmp)
![iconadicionaNodo](bmp/adicionaNodo.bmp)