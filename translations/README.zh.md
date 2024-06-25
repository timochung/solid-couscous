# 标题测试

样例代码测试：

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
![](./translated_images/bicycle.e5987a077c36459b31452b5f6322a930fe95440ab29aeb9c7cbea92148cbe694.zh.png)


免责声明：该翻译是由人工智能模型翻译的，可能不完美。请查看输出并进行必要的更正。