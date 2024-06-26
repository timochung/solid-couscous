# Titre de Test

Test de code d'exemple :

```
import os
import dotenv
from openai import AzureOpenAI

# Chargement des variables d'environnement
dotenv.load_dotenv()

# Récupération des informations liées à Azure OpenAI depuis les variables d'environnement
aoai_endpoint = os.getenv('AZURE_OPENAI_ENDPOINT')
aoai_key = os.getenv('AZURE_OPENAI_API_KEY')
aoai_version = os.getenv('AZURE_OPENAI_VERSION')

# Initialisation du client Azure OpenAI
client = AzureOpenAI(
    azure_endpoint=aoai_endpoint,
    api_key=aoai_key,
    api_version=aoai_version
)


```



![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Google_Images_2015_logo.svg/1200px-Google_Images_2015_logo.svg.png)
![](/./translated_images/bicycle.bd903e5d4d1ae4db0679cf423771fdd2e129c48627fd83ff05594a4897f85947.fr.png)


Avertissement : La traduction a été effectuée à partir d'un modèle d'IA et peut ne pas être parfaite. Veuillez examiner le résultat et apporter les corrections nécessaires.