# aiml

```
import requests
url = 'https://raw.githubusercontent.com/mrjeevan/aiml/main/Backpropagation.ipynb'
r = requests.get(url, allow_redirects=True)
open('name.ipynb', 'wb').write(r.content)
```
