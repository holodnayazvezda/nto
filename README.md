# NTO QUICK START GUIDE

Полезное ПО:
- **VPN hiddify** -  скачивать [тут](https://github.com/hiddify/hiddify-app/releases/tag/v2.0.5)
ключ для VPN:
`vless://e65a4d1d-cd94-4387-b649-ba6e7f77a4c2@v-chat.ru:36872?type=tcp&security=reality&pbk=0zBB1BxfO3XSd7cjjmlpKoDAjB9d536t1YMv9qGtnRk&fp=random&sni=yahoo.com&sid=df084b9f&spx=%2F#NTO%20%26%20Samsung%20Championship-k4xezuw4`
- **InteliJ IDEA Ultimate** скачивать [тут](https://www.jetbrains.com/idea/download/?section=windows)
- **proxy для ide'шек**:
http
v-chat.ru
18811
без аунтентификации
- https://giga.chat/, https://gigacode.ru/#/%23connect
- https://chat.deepseek.com/
- https://chatgpt.com
- [любимый supabase](https://supabase.com/dashboard/project/ejhhfptkoaeawgnguynb)
- qwen..
- Любимый api'шник J4F
```python
from g4f.client import Client
import g4f.Provider.Blackbox as bb

client = Client()
response = client.chat.completions.create(
model=['blackboxai', 'blackboxai-pro', 'llama-3-1-405b', 'deepseek-r1', 'gpt-4o'][0],
messages=[{"role": "user", "content": "Hello"}],
provider=bb,
web_search=False
)
print(response.choices[0].message.content)
```
- **Чистая архитектура в Spring (пример):**
https://github.com/vinimrs/spring-boot-clean-architecture/
- **Настройка application.properties для postgres**

- 45.151.30.221 31.207.45.85 rroo
```spring.jpa.hibernate.ddl-auto=update

spring.datasource.driver-class-name=org.postgresql.Driver
spring.datasource.username=${POSTGRES_USERNAME:postgres}
spring.datasource.password=${POSTGRES_PASSWORD:postgres}
spring.datasource.url=${POSTGRES_JDBC_URL}
```