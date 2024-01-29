# Minecraft Server Download/Software API

## MC-SRV-DL-API Lets you easily download minecraft server software such as paper, purpur or vanilla all in one place.

### It can be used to always get the latest server software or as a replacement for the now archived Yive's mirror.

The Minecraft Server Software API let's you download server softwares with ease. As of right now, these are:

- 📜Paper
- 🎶Purpur
- 🎉Vanilla
- 🗿MohistMc

Some of the other server softwares that are planned to be added:

- 🌟Glowstone
- 🔥Magma
- 👖Fabric

To download one, use the /download/{SOFTWARE}/{VERSION}/{BUILD}.

To grab the latest paper .jar download:

`
GET https://jar.setup.md/download/paper/latest/latest
`

This will redirect you to the .jar file.

To grab the latest vanilla server.jar download link: (no build parameter required)

`
GET https://jar.setup.md/download/vanilla/latest
`

**This code goes by the Code Credit License, included in the LICENSE.md file. Original author: Aleksander Wegrzyn (or polish-penguin-dev). Modified by setup.md team to work in Cloudflare Workers**

