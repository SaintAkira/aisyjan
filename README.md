# saint music bot — for playing music and having fun💖

## Requirements

This bot needs a Linux system, Node JS version 15 or newer with the packages specified in the `package.json`, ffmpeg, Google Chrome or Chromium to work.

## Deployment

### Config

1. Copy `example.env` to `.env` and fill it with your credentials.
2. Install the required Node JS packages:
    ```bash
    npm install
    ```
3. Run:
    ```bash
    npm start
    ```

### Docker

1. Build:
    ```bash
    docker build -t musicplayer .
    ```
2. Run:
    ```bash
    docker run --env-file .env musicplayer
    ```

### Heroku

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/SaintAkira/aisyjan/blob/main/app.json)

-   ### Generate String Using Replit⤵️

<a href="https://replit.com/@SaintAkira/AgI-sRIng-sssIn-1?v=1"><img src="https://img.shields.io/badge/run-string__session.py-magenta?style=for-the-badge&logo=repl.it" alt="generate_string" /></a>

## Commands

| Command | Usage                                          |
| ------- | ---------------------------------------------------- |
| /play   | play the replied audio file                          |
| /pause  | pause the audio stream                               |
| /resume | resume the audio stream                              |
| /skip   | skip the current audio stream                        |
| /stop   | clear the queue and remove the userbot from the call |

## License

### GNU Affero General Public License v3.0

[Read more](http://www.gnu.org/licenses/#AGPL)

## Credits

-   Andrew Lane ([TGCalls](https://github.com/tgcallsjs/tgcalls))
-   Painor ([GramJS](https://github.com/gram-js/gramjs))
-   Vitaly Domnikov ([Telegraf](https://github.com/telegraf/telegraf))
-   Lonami ([Telethon](https://github.com/lonami/telethon))
