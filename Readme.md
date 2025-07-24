<a href="https://g-status.ecoguardiao.tech/status/kiritoapi"> <img alt="Status Api" src="https://g-status.ecoguardiao.tech/api/badge/4/status">
    </a>

    
Para instalar a kiritoapi na sua aplicação basta utilizar 

```npm i kiritoapi```

No console.

# Rotas da KiritoApi

```js
const KiritoApi = require("kiritoapi")
const api = new KiritoApi()

//Minecraft Info
await api.mineinfo("mc.sparklypower.net")

//Minecraft Banner
await api.minebanner("mc.sparklypower.net")

//Discord UserInfo
await api.userinfo("820344895528632380")

//Discord SetBanner
await api.setBannerBot("Client-Token", "Link do Banner")

//Discord Invite Info
await api.inviteInfo("Link de um Servidor")

//ChatIA
await api.chat("oii")

//GitHub UserInfo
await api.GithubUserinfo("Nome do Github")

//YouTube CanalInfo
await api.youtubeInfo("Nome do Canal")

//Tradutor
await api.tradutor("Texto que sera traduzido", "linguagem que o texto vai ser traduzido exemplo: en = inglês")

//Musica Lyrics
await api.MusicLyrics("Nome do cantor", "nome da musica")
```

Agradecemos por utilizar nossa package.


Base Feita Pelo: https://github.com/shindozk
