var Bot = require('discord-bot-Nickname');
 
});
 
bot
    .on(bot.triggers.command, 'hello')
    .do(function(bot, conf, args) {
        this.reply('world');
    });
 
bot.connect();

bot
    .on(bot.triggers.react, /hey|hello/)
    .do(function(Test) { /* <- this is the task */
        console.log(args.message);
    });
