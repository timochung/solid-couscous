# Titre Test

Test du code d'exemple:

```
import os
import dotenv
from openai import AzureOpenAI

# Charger les variables d'environnement
dotenv.load_dotenv()

# Obtenir les informations relatives à Azure OpenAI à partir des variables d'environnement
aoai_endpoint = os.getenv('AZURE_OPENAI_ENDPOINT')
aoai_key = os.getenv('AZURE_OPENAI_API_KEY')
aoai_version = os.getenv('AZURE_OPENAI_VERSION')

# Initialiser le client Azure OpenAI
client = AzureOpenAI(
    azure_endpoint=aoai_endpoint,
    api_key=aoai_key,
    api_version=aoai_version
)


```



![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Google_Images_2015_logo.svg/1200px-Google_Images_2015_logo.svg.png)
![](./translated_images/bicycle.e5987a077c36459b31452b5f6322a930fe95440ab29aeb9c7cbea92148cbe694.fr.png)


Avertissement : La traduction a été traduite à partir de l'original par un modèle d'IA et peut ne pas être parfaite. Veuillez examiner la sortie et apporter toutes les corrections nécessaires.