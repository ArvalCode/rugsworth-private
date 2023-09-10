# Rugsworth

A discord bot written in Rust with the assistance of Songbird and Serenity.
## Features

- **Rust**
- **Play songs** from Youtube using a url or a search phrase
- Add complete Youtube **playlists** to the song queue
- **Maintain a queue** of songs which you can pause, skip and resume
- **ChatGPT** integration (Void for now)
- **Easy to use**

## How to install

1. Install latest version of rust
2. Intall [yt-dlp](https://github.com/yt-dlp/yt-dlp#installation)
3. Clone the repository
4. Install [ffmpeg](https://ffmpeg.org/).
5. Create a discord bot so you can run the bot local on your computer
6. Set the environment variables (.env files) use current one as example
7. You should be able to run `cargo run` successfully

# rugsworth-private
Project to suffice the need to learn programming in Rust.


# How to download on Windows Linux Sybsystem
1. Downloads Window Linux Subsystem using microsoft store
2. Update repositories by doing 'sudo apt update'
3. Download rust by doing 'sudo apt install rustup'
4. Open File Explorer on Windows and go to /Ubuntu/home/{USERNAME}/ and create a downloads folder there to store the bot
5. cd /home/{USERNAME}/downlaods/rugsworth-private
6. Before you run the bot, you must download cmake, openssl-sys (If it still gives an error, download whatever it is missing and create an issue regarding it posted with error code for help)
7. 'cargo run'
