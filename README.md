# Blabot CLI

Command line interface for Blabot engine


## Installation

    $ npm install -g blabot-cli

## Use

Create new dictionary "mydict":

    $ blabot init mydict

Add some text into dictionary:

    $ blabot parse mydict.json "Hey, you! Is this some text? Yep, it is good text" 

Generate some blabols:
    
    $ blabot sentence mydict.json

For more help see:

    $ blabot --help
