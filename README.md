var Bot = require('discord-bot');
 
var bot = new Bot({
    email: <email>,
    password: <pass>
});
 
bot
    .on(bot.triggers.command, 'hello')
    .do(function(bot, conf, args) {
        this.reply('world');
    });
 
bot.connect();
{
*name*: *discord-bot-Nickname*,
*version*: *0.1.0*
*description*: "",
*main*: *bot.js*
*scripts*: [
*test*: *nodemon bot.js*
},
