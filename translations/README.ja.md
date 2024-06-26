# タイトル テスト

サンプルコードのテスト：

```
import os
import dotenv
from openai import AzureOpenAI

# 環境変数をロード
dotenv.load_dotenv()

# Azure OpenAIに関連する情報を環境変数から取得する
aoai_endpoint = os.getenv('AZURE_OPENAI_ENDPOINT')
aoai_key = os.getenv('AZURE_OPENAI_API_KEY')
aoai_version = os.getenv('AZURE_OPENAI_VERSION')

# Azure OpenAIクライアントを初期化する
client = AzureOpenAI(
    azure_endpoint=aoai_endpoint,
    api_key=aoai_key,
    api_version=aoai_version
)


```



![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Google_Images_2015_logo.svg/1200px-Google_Images_2015_logo.svg.png)
![](/./translated_images/bicycle.2f48d52f09c83f183efa9ee7b5e90d9f0327308f24b5e34d0d76f544161ca2e2.ja.png)


免責事項：この翻訳はAIモデルによって元の翻訳から翻訳され、完璧であるとは限りません。
出力を確認し、必要に応じて修正してください。