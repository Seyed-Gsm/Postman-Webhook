# [Postman-Webhook](https://discord.gg/KeuBYBbErh)
> Send A Webhook Message ( Embed / Content ) With Postman
</br>
<div align="center">
  <img src="https://cdn.discordapp.com/attachments/844973689292193824/953941703440597002/postman.png">
  </div>


## You Need:
- [**Postman**](https://www.postman.com/downloads) </br>
- [**Discord**](https://discord.com/download)
</br>

## Getting Started
- Create A Request ( Request Type " POST " ) </br>
![POST](https://cdn.discordapp.com/attachments/844973689292193824/953939259662958592/unknown.png) </br>
- Put Your Webhook URL In " Request URL " </br>
![URL](https://cdn.discordapp.com/attachments/844973689292193824/953939707341963354/unknown.png) </br>
- Select " Body " </br>
![body](https://user-images.githubusercontent.com/83529331/158773411-149f77a2-3164-4917-ad3d-a9cf7769997a.png) </br>
- Now Select " Raw " And " Json " </br>
![Type](https://user-images.githubusercontent.com/83529331/158773644-ca95de1b-213d-4389-b5dc-f6e43421904c.png)
- Now You Should Write Your Embed Content In Postman Editor, Like This: 
```json
{
  "content": null,
  "embeds": [
    {
      "description": "Henlo Frens",
      "color": 16729856,
      "author": {
        "name": "Pyr33x",
        "icon_url": "https://cdn.discordapp.com/attachments/844973689292193824/952965019119800320/0c001137084652d71854914b9637111b-modified.png"
      }
    }
  ]
}
```
- And Send Requset
- Done!
