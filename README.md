<h1 align="center">Application Bot</h1>
<p align="center">
  <img style="border-radius:50%;" width="300" height="300" src="https://h.top4top.io/p_1873t456n1.png" alt="KMCODES Logo">
</p>


<p align="center">KINGMAN Application Bot</p>

<p align="center">It is a Discord bot whose goal is to make it easier for server owners to create a so-called administration submission</p>


<p align="center">The bot needs a <a href="https://www.mongodb.com/">MongoDB </a></p>


<h3 align="center">Features</h3>


- [x] You can put your own questions in the bot  
- [x] Select Apply Channel
- [x] Select Role 
- [x] Accept and reject by clicking on the reaction or manually
- [x] Easily add and remove questions
- [x] MongoDB Database
- [x] You can block someone from applying again
- [x] No one can apply if he is under review


<h2 align="center">How to use</h2>


*  Go to me-config.json File and put thes info


```json
{
    "prefix": "."
}
```
* Create a  filename .evn and put this info


```env
ME_TOKEN = OTU2OTA3NDg1NTIyOTY4NjQ2.G5WKee.9sV3kpUc3swZELRG7RbevrMvXzwZvGPmAIwAS0
ME_MONGO = MongoDB Url
```

* You must download the `packages`

```json
"dependencies": {
    "ascii-table": "0.0.9",
    "colors": "^1.4.0",
    "discord.js": "^12.5.3",
    "express": "^4.17.1",
    "figlet": "^1.5.0",
    "mongoose": "^5.12.13"
  },
```

* Run the bot via `node index.js`
* If you want to run a 24-hour bot, I recommend [Repl.it](https://replit.com/)
* If you like the bot, please put a star to continue
