# TwitCasting Recorder

Just another Python implementation of [TwitCasting](https://twitcasting.tv/) live stream recorder.

## Usage

Install dependencies with `pip install -r requirements.txt`.\
**Install ffmpeg manually if you haven't.**

```text
usage: main.py [-h] [--proxy PROXY] [--user-agent USER_AGENT] [-o FILENAME] user_id

TwitCasting live stream recorder.

positional arguments:
  user_id               The user id to record.
                        i.e. the string after "https://twitcasting.tv/" in URL

optional arguments:
  -h, --help            show this help message and exit
  --proxy PROXY         Request with HTTP proxy. e.g. http://127.0.0.1:1080
  --user-agent USER_AGENT
                        Request with custom User Agent.
  -o FILENAME, --output FILENAME
                        File name to save recorded video.
```

## Thanks

- [himananiito/livedl](https://github.com/himananiito/livedl)
- [nekoteaparty/Alice-LiveMan](https://github.com/nekoteaparty/Alice-LiveMan)
- [prinsss/twitcasting-recorder](https://github.com/prinsss/twitcasting-recorder)

## License

<img src="https://github.com/jim60105/twitcasting-recorder/assets/16995691/f433994f-0d6f-4ce1-985c-2a59ef3b87a9" alt="open graph" width="200" />

[GNU GENERAL PUBLIC LICENSE Version 3](LICENSE)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
