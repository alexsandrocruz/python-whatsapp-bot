This is a bot written in python that runs in whatsapp and is purely an extension of [yowsup](https://github.com/tgalal/yowsup).

# NOTICE #
Since Facebook has taken WhatsApp over, and since WhatsApp itself does not like developers so much, I have quit all activity on this repository.
The instructions to install will soon start failing when yowsup upgrades to the version that allows encryption.
If at all you're interested in building bots while having fun, checkout Telegram messenger and [yagop/telegram-bot](https://github.com/yagop/telegram-bot).

I hope you realize how much of a pain it is to develop for WhatsApp. But in case any of you decide to pay me $160 or above, I'll be happy to update it to a more working version. 

## CAUTION ##
Although this used to work fine, I got two numbers banned(?) in late August, 2014.
So, please be warned.

##Installation##
The installation process is quite simple

#### One Time steps####

    git clone https://github.com/asdofindia/python-whatsapp-bot.git
    cd python-whatsapp-bot
    git submodule init
    git submodule update

#### Associating with account ####
Follow [https://github.com/tgalal/yowsup/wiki/yowsup-cli#registration](https://github.com/tgalal/yowsup/wiki/yowsup-cli#registration) and register a number. After registering you must have created a config file as mentioned [here](https://github.com/tgalal/yowsup/wiki/yowsup-cli#your-login-credentials) like [this](https://github.com/tgalal/yowsup/blob/master/src/config.example)
Place the config file in `configs` folder.

## Running the bot ##
    python bot.py -c configs/<yourconfig> -b -a -k

if -c is not specified, `configs/config` will be used.

## Contribute ##

#### Report errors ###
I have tried to use modules that are already available in python. If any missing module error is thrown, try `pip install <modulename>`.
Please [create an issue](https://github.com/asdofindia/python-whatsapp-bot/issues) if you have errors that needs fix

#### Develop modules ####
Read modules in the modules folder and create your own modules.
If possible teach me python and refactor this mess.
Send pull requests, I'll merge them if I know how to :P


## Credits ##
* [tgalal](https://github.com/tgalal) for [yowsup](https://github.com/tgalal/yowsup) which is the most important reason this project is possible.
* [Schumix](https://github.com/Schumix) for [chatterbotapi](https://github.com/Schumix/ChatterBotApi)
* Countless people on [StackOverflow](http://stackoverflow.com) for numerous code snippets


##About
Look at my [older implementation](https://github.com/asdofindia/pyWhatsapp) to know more about how that used to work.
