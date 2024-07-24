# Python-Tutorial

## Make Sure use this command to install Sanic
```pip install Sanic```

## Code Down Here!
from sanic import Sanic
from sanic.response import text

app = Sanic("MyHelloWorldApp")

@app.get("/")
async def helloworld(request):
    return text("Hello, world.")


if name == "_main":
    app.run(host="localhost", port=69)
