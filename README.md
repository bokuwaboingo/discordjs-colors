# Discord.JS Colors
List of the colors used in [Discord.JS](https://discord.js.org)'s Type Definition, [ColorResolvable](https://discord.js.org/#/docs/main/stable/typedef/ColorResolvable).

Here's how to do this:

Install the package.
```
npm install discordjs-colors
```

Then do something like this.
```js
const Discord = require("discord.js");
const client = new Discord.Client();
const colors = require("discordjs-colors");

client.on("message", (message) => {
    let embed = new Discord.RichEmbed()
    .setTitle("Red color")
    .setColor(colors.red());

    message.channel.send(embed);
})
```

Or this:
```js
const chalk = require("chalk");
const colors = require("discordjs-colors");

console.log(chalk.hex(colors.red())("Red text"))
```

Or you can run it:
```
discordjs-colors
```

You can find the color list [here](docs/COLORS.md).

## [Github](https://github.com/hiimjustin000/discordjs-colors)
## [NPM Package](https://www.npmjs.com/package/discordjs-colors)