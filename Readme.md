import requests

BASE_URL = 'https://fakestoreapi.com'

response = requests.get(f"{BASE_URL}/products")
print(response.json())
print(response.status_code)

https://www.freecodecamp.org/news/how-to-interact-with-web-services-using-python/


tar -czvf website.tar.gz -C website .
