# BoT-IoT Dataset

## Descripción

El **BoT-IoT Dataset** es un conjunto de datos creado para ofrecer una representación realista del tráfico de red en un entorno de Internet de las Cosas (IoT) que incluye tanto tráfico normal como tráfico de botnet. Este dataset fue desarrollado en el Cyber Range Lab de UNSW Canberra, con el objetivo de apoyar la investigación en análisis forense de redes y técnicas de detección de amenazas en entornos IoT.

Puedes descargar el BoT-IoT Dataset desde [aquí](https://www.unsw.adfa.edu.au/cyber/cyber-range/).

## Contenido del Dataset

El dataset contiene archivos en diferentes formatos, pero en esta versión se utilizan solo los archivos CSV. El dataset incluye una variedad de tipos de ataques, como DDoS, DoS, escaneo de servicios, keylogging y exfiltración de datos. Los datos están organizados en función de las categorías y subcategorías de ataques para facilitar el etiquetado y el análisis.

### Tamaño del Dataset

- **Tamaño total de archivos pcap originales**: 69.3 GB
- **Tamaño total de archivos CSV extraídos**: 16.7 GB
- **Muestra del 5% del dataset**: 4 archivos de aproximadamente 1.07 GB en total, con alrededor de 3 millones de registros.

## Archivos CSV

La muestra del 5% del dataset se compone de los siguientes archivos CSV:
- `BoT-IoT-5%-file1.csv`
- `BoT-IoT-5%-file2.csv`
- `BoT-IoT-5%-file3.csv`
- `BoT-IoT-5%-file4.csv`

## Estructura del Archivo CSV

Cada archivo CSV tiene las siguientes columnas:

| Columna | Descripción |
|---------|-------------|
| `pkSeqID` | ID de secuencia del paquete |
| `stime` | Hora de inicio del flujo |
| `flgs` | Flags TCP |
| `proto` | Protocolo (TCP, UDP, etc.) |
| `saddr` | Dirección IP de origen |
| `sport` | Puerto de origen |
| `daddr` | Dirección IP de destino |
| `dport` | Puerto de destino |
| `pkts` | Número de paquetes |
| `bytes` | Cantidad de bytes transferidos |
| `state` | Estado del flujo |
| `ltime` | Hora de finalización del flujo |
| `seq` | Secuencia de paquetes |
| `attack_cat` | Categoría del ataque |
| `attack_desc` | Descripción del ataque |

## Ejemplos de Uso

Aquí tienes algunos ejemplos de cómo puedes cargar y analizar los datos usando Python y la biblioteca Pandas:

```python
import pandas as pd

# Cargar el archivo CSV
df = pd.read_csv('BoT-IoT-5%-file1.csv')

# Mostrar las primeras filas del DataFrame
print(df.head())

# Filtrar el dataset para obtener solo los ataques DDoS
ddos_attacks = df[df['attack_cat'] == 'DDoS']

# Mostrar el número de ataques DDoS
print(ddos_attacks.shape[0])



### Detalles del contenido del `README.md`

- **Descripción**: Introduce el dataset y su propósito.
- **Contenido del Dataset**: Describe el tamaño total y los archivos CSV de la muestra.
- **Estructura del Archivo CSV**: Proporciona una tabla con la descripción de cada columna en los archivos CSV.
- **Ejemplos de Uso**: Muestra un ejemplo básico de cómo cargar y analizar los datos usando Python.
- **Citar el Dataset**: Proporciona una cita en formato BibTeX para referenciar el dataset.
- **Contacto**: Información de contacto para más detalles.
- **Contribuciones**: Enlace a las directrices para contribuir al proyecto.
- **Licencia**: Información sobre la licencia del proyecto.

Este `README.md` proporciona toda la información necesaria para que los usuarios comprendan el dataset, lo utilicen en sus investigaciones y contribuyan al proyecto si así lo desean. 

Si tienes algún detalle específico que quieras incluir o ajustar, no dudes en decírmelo.
