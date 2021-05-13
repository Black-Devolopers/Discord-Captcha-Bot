<h1 align="center">Discord Simplet Captcha Bot </h1>
A Discord bot that requires users to answer a captcha to enter in your server. This bot is brand new and in beta so please do not expect it to be perfect.

# Requirements
### discord.py and captcha

Tested with Python 3.7 on Windows 10...

# Features
- Sets a user to a limited role upon joining the server.
- DM's the user a captcha to solve to have the role removed.
- Allows the user to request a new captcha if the current one is too hard.

# Setup Instructions ( In Replit or Glitch )

[![Run on Repl.it](https://repl.it/badge/github/Black-Devolopers/Discord-Captcha-Bot)](https://repl.it/github/Black-Devolopers/Discord-Captcha-Bot)
[![Remix on Glitch](https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg)](https://glitch.com/edit/#!/import/github/Black-Devolopers/Discord-Captcha-Bot)

- Install the required modules!
- Create a new application at https://discordapp.com/developers/applications
- Turn it into a bot. Copy the token and put it on line 65 of `DiscordCaptcha.py`
- On the developer portal, Select `OAuth2`
- Select the `bot` checkmark and then `Manage Roles`
- Copy the generated link and paste it in your browser. Select the server to add it to.
- Go to your server settings and find roles. Move the bot role above all user roles.
- Create your limited role and ensure that it is below the bot's role.
- Now, Disable the read message permission for that role from the channel for which you want that role should not read the content!
- Copy the limited role's ID and put it on line 11 of `DiscordCaptcha.py`
- Copy your server's ID and put it on line 13 of `DiscordCaptcha.py`
- type in the terminal `python DiscordCaptcha.py`




# Setup Instructions ( In Windows )
- Install the required modules!
- Create a new application at https://discordapp.com/developers/applications
- Turn it into a bot. Copy the token and put it on line 65 of `DiscordCaptcha.py`
- On the developer portal, Select `OAuth2`
- Select the `bot` checkmark and then `Manage Roles`
- Copy the generated link and paste it in your browser. Select the server to add it to.
- Go to your server settings and find roles. Move the bot role above all user roles.
- Create your limited role and ensure that it is below the bot's role.
- Now, Disable the read message permission for that role from the channel for which you want that role should not read the content!
- Copy the limited role's ID and put it on line 11 of `DiscordCaptcha.py`
- Copy your server's ID and put it on line 13 of `DiscordCaptcha.py`
- Run `DiscordCaptcha.py`



## ✨ Contributors :


<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<table>
  <tr>
     <td align="center"><a href="https://github.com/DeltaCoderr"><img src="https://avatars.githubusercontent.com/u/78690237?v=4" width="100px;" alt=""/><br /><sub><b>MSVFORYOU</b></sub></a><br /><a href="https://github.com/MSVFORYOU" title="Owner">👑</a></td>
     
     
  </tr>
  
</table>
