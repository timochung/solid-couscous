# عنوان الاختبار

اختبار الشفرة العينية:

```
import os
import dotenv
from openai import AzureOpenAI

# تحميل متغيرات البيئة
dotenv.load_dotenv()

# الحصول على معلومات Azure OpenAI ذات الصلة من متغيرات البيئة
aoai_endpoint = os.getenv('AZURE_OPENAI_ENDPOINT')
aoai_key = os.getenv('AZURE_OPENAI_API_KEY')
aoai_version = os.getenv('AZURE_OPENAI_VERSION')

# تهيئة عميل Azure OpenAI
client = AzureOpenAI(
    azure_endpoint=aoai_endpoint,
    api_key=aoai_key,
    api_version=aoai_version
)


```



![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Google_Images_2015_logo.svg/1200px-Google_Images_2015_logo.svg.png)
![](./translated_images/bicycle.e5987a077c36459b31452b5f6322a930fe95440ab29aeb9c7cbea92148cbe694.ar.png)


تنويه: تم ترجمة الترجمة من الأصل بواسطة نموذج AI وقد لا تكون مثالية. يرجى مراجعة النتائج وإجراء أي تصحيحات ضرورية.