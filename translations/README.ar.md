# اختبار العنوان

اختبار الكود العيني:

```
import os
import dotenv
from openai import AzureOpenAI

# تحميل المتغيرات البيئية
dotenv.load_dotenv()

# الحصول على معلومات Azure OpenAI ذات الصلة من المتغيرات البيئية
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
![](/./translated_images/bicycle.603f93ce54f047852dc5b46ae95b29f3f7e631fbe7dea0c21e2ec2ce674bc497.ar.png)


تنويه: تم ترجمة الترجمة من مصدرها الأصلي باستخدام نموذج AI وقد لا تكون مثالية. يرجى مراجعة النتيجة وإجراء أي تصحيحات ضرورية.