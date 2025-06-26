# Conceptos-Basicos-NPL
Preprocesamiento de noticias con NLP: limpieza, tokenización, eliminación de stopwords y stemming en español.

# Procesamiento de Lenguaje Natural (NLP) de Noticias

## Descripción

Este proyecto realiza un preprocesamiento básico de datos textuales en español aplicando técnicas fundamentales de **Procesamiento de Lenguaje Natural (NLP)** a un conjunto de noticias. El objetivo es limpiar, estructurar y preparar los textos para tareas posteriores como análisis semántico o clasificación.


## Dataset

- Archivo JSON con noticias crudas (`noticias.txt`)
- Cada entrada contiene un `titular` y un `texto` asociado


##  Proceso de Preprocesamiento

1. **Carga de datos**
   - Conversión del archivo JSON a un DataFrame de Pandas
2. **Limpieza de texto**
   - Eliminación de caracteres especiales
   - Normalización de espacios y conversión a minúsculas
3. **Tokenización**
   - Uso de `ToktokTokenizer` para dividir el texto en palabras
4. **Eliminación de Stopwords**
   - Eliminación de palabras vacías en español y números
5. **Stemming**
   - Reducción de palabras a sus raíces usando `SnowballStemmer` para español


##  Tecnologías

- Python 3
- Pandas
- NLTK
- ToktokTokenizer

---

## Conclusión

Este pipeline de NLP básico demuestra cómo preparar textos en español para análisis posteriores. La personalización del preprocesamiento según el dominio es crucial para obtener representaciones relevantes. Aunque el stemming sacrifica precisión semántica, es útil para tareas de exploración rápida o clasificación general.



