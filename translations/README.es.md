# Título de Prueba

Prueba del código de muestra:

```
import os
import dotenv
from openai import AzureOpenAI

# Cargar variables de entorno
dotenv.load_dotenv()

# Obtener información relacionada con Azure OpenAI de las variables de entorno
aoai_endpoint = os.getenv('AZURE_OPENAI_ENDPOINT')
aoai_key = os.getenv('AZURE_OPENAI_API_KEY')
aoai_version = os.getenv('AZURE_OPENAI_VERSION')

# Inicializar el cliente de Azure OpenAI
client = AzureOpenAI(
    azure_endpoint=aoai_endpoint,
    api_key=aoai_key,
    api_version=aoai_version
)


```



![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Google_Images_2015_logo.svg/1200px-Google_Images_2015_logo.svg.png)
![](./translated_images/bicycle.e5987a077c36459b31452b5f6322a930fe95440ab29aeb9c7cbea92148cbe694.es.png)


Descargo de responsabilidad: La traducción fue realizada por un modelo de inteligencia artificial y puede no ser perfecta. Por favor, revise el resultado y haga las correcciones necesarias.