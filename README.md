# LLM-Chatbot

* Para ejecutar este proyecto, es posible clonar el repositorio a un ambiente como colab o saturn cloud y ejecutar VectorDB.ipynb y posteriormente Prompt Engineering.ipynb.

* VectorDB creara la base de datos vectorizada con la informacion de las facturas pagadas, la cual se usara en el siguiente notebook.

* En Prompt Engineering.ipynb se carga el modelo de databricks Dolly-3B, el tamaño seleccionado se da por las restricciones de memoria de ambientes gratuitos como colab. Si se utiliza un modelo más especializado, los resultados mejoraran en gran manera.

* Opciones de mejora: Añadir el resto de la informacion del archivo json. Es necesario estandarizar la informacion y garantizar que haya coherencia en lo que se genera pues se presentan documentos que no pueden ser leido con mayor facilidad. Implementando un modelo mas robusto como Mistral-7B o Mixtral8x7B el modelo podrá generalizar con mayor facilidad, lo cual simplificaria el desarrollo extra de la segunda fuente de informacion.


## Preguntas y dudas

* En caso de tener cualquier tipo de pregunta/duda sobre este ejemplo, contactarme al correo: sgamboa456@gmail.com
