# aiml

```
import requests
name = 'second'
url = f'https://raw.githubusercontent.com/mrjeevan/aiml/main/{name}.ipynb'
r = requests.get(url, allow_redirects=True)
open(f'{name}.ipynb', 'wb').write(r.content)
```
