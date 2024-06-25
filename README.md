# Title Test

Test of sample code:

```
import os
import dotenv
from openai import AzureOpenAI

# 加载环境变量
dotenv.load_dotenv()

# 从环境变量中获取 Azure OpenAI 相关信息
aoai_endpoint = os.getenv('AZURE_OPENAI_ENDPOINT')
aoai_key = os.getenv('AZURE_OPENAI_API_KEY')
aoai_version = os.getenv('AZURE_OPENAI_VERSION')

# 初始化 Azure OpenAI 客户端
client = AzureOpenAI(
    azure_endpoint=aoai_endpoint,
    api_key=aoai_key,
    api_version=aoai_version
)


```



![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Google_Images_2015_logo.svg/1200px-Google_Images_2015_logo.svg.png)
![](bicycle.png)
