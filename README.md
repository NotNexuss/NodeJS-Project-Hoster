# 24/7 Hosting Script
### You can now host your repl on repl.it 24/7 without hacker plan!
<br>

# Node.JS (python below)

<br>
Open your main repl file (example: index.js, app.js, main.js etc...) and leave a space at the very top of the file, and paste this code in:
<br>
</br>

```
const express = require('express')
const app = express();
const port = 3000

app.get('/', (req, res) => res.send('<meta http-equiv="refresh" content="0; URL=https://itzsidhan.gitbook.io/itzsidhan/support"/>'))

app.listen(port, () =>
console.log(`Enabled 24/7 Hosting.`)
);
```

Now go to the shell, and paste:

```
npm install express
```

Run the repl, and copy the web address you see top right corner. And go to [UptimeRobot](https://uptimerobot.com/) and host your web address.

<br>
</br>

# Python

<br>
</br>

Open your main repl file (example: main.py etc...) and add `keep_alive` to import line. Now create a new file named `keep_alive.py`, then paste this script below:
```
from flask import Flask
from threading import Thread

app = Flask('')

@app.route('/')
def main():
    return '<meta http-equiv="refresh" content="0; URL=https://itzsidhan.gitbook.io/itzsidhan/support"/>'

def run():
    app.run(host="0.0.0.0", port=8080)

def keep_alive():
    server = Thread(target=run)
    server.start()
```

<br>

Run the repl, and copy the web address you see top right corner. And go to [UptimeRobot](https://uptimerobot.com/) and host your web address.

<br>

### Contact me: 

[<img align="left" alt="ItzSidhan | YouTube" width="22px" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/395_Youtube_logo-128.png" />](https://bit.ly/ItzSidhanYT)
<a href="https://dsc.gg/itzsidhan">
  <img align="left" alt="Discord" width="23px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/discord.svg" />
</a>
<a href="https://twitter.com/ItzSidhan">
  <img align="left" alt="Twitter" width="23px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/twitter.svg" />
</a>

</br>

### Languages and Tools: 

[<img align="left" alt="JavaScript" width="26px" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/187_Js_logo_logos-128.png" />](https://www.javascript.com/)
[<img align="left" alt="Node.js" width="26px" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/233_Node_Js_logo-128.png" />](https://nodejs.org/en/)
[<img align="left" alt="GitHub" width="26px" src="https://cdn4.iconfinder.com/data/icons/socialcones/508/Github-128.png" />](https://github.com/)
[<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />](https://code.visualstudio.com/)
<br />
<br />
