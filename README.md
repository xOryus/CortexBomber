# CortexBomber
Fast, discreet and efficient, Script developed in Python 3 for SMS Bomber.

# Come here my dear colleague, I'll teach you

# how to use this kludge

## Features

- Lots of integrated SMS APIs, and support for custom API configu>

- Unlimited number of SMSs (with proxy support for huge bombs!).

- Faster and lighter than most SMS Bomber apps/scripts.

- International bombing available.

## Requirements

- Python 3.6+ on Android ([Termux](https://termux.com)), and Linu>

NOTE: Windows not supported as some of `httpx`'s `http2` librarie>

## Instructions for Android

- Download Termux from the [F-Droid]

- Open Termux and enter the following commands:

```bash

# Install Dependencies:

pkg install git python -y

# Clone this repo

git clone (SOON - EM BREVE)

# Move into working directory.

cd CortexBomber

# Install the requirements.

pip3 install -r requirements.txt

```

## Instructions for iOS/iPadOS(due to the way Apple devices handl>

Open [iSH] and enter the following commands:

```bash

# Install Dependencies:

apk add git

apk add python3

apk add py3-pip

# Clone this repo

git clone (SOON - EM BREVE)

# Move into working directory.

cd CortexBomber

# Install the requirements.

pip3 install -r requirements.txt

```

## Instructions for Debian-based GNU/Linux distributions:

```bash

# Install Dependencies:

sudo apt install git python3 python3-pip

# Clone this repo

git clone (SOON - EM BREVE)

# Move into working directory.

cd CortexBomber

# Install the requirements.

pip3 install -r requirements.txt

```

## Options

You can also read this via `python3 bomber.py -h` or `python3 bomber.py --help`

```

[BYELORDY] CortexBomber - Simple, practical and efficient. Raise your level!

Usage: bomber.py [--config-path/-c] [--num/-N] [--country/-C] [--threads/-T]

                 [--timeout/-t] [--proxy/-P] [--verbose/-v] [--verify/-V]

                 [-h/--help] TARGET

Positional arguments:

  TARGET             Target mobile number without country code.

Optional arguments:

  --config-path, -c  Path to API config file. (NOTE: the file must be in JSON format!) (default: 'api_config.json')

  --num, -N          Number of SMSs to send to TARGET. (default: 30)

  --country, -C      Country code without (+) sign. (default: 91)

  --threads, -T      Max number of concurrent HTTP(s) requests. (default: 15)

  --timeout, -t      Time (in seconds) to wait for an API request to complete. (default: 10)

  --proxy, -P        Use proxy for bombing. (Recommended for large number of SMSs)

  --verbose, -v      Enables verbose output, for debugging.

  --verify, -V       To verify all providers are working or not.

  -h, --help         Display this message.

I DON'T TAKE RESPONSIBILITY FOR YOUR FAILURES, USE WITH CAUTION AND ALWAYS BEHIND A PROXY OR VPN!

(NÃO ME RESPONSABILIZO PELOS SEUS ATOS FALHOS, USE COM CAUTELA E SEMPRE ATRÁS DE UM PROXY OU VPN!)

[BYELORDY - https://github.com/byelordy]

```

## Examples

```bash

# The default - 25 threads, 50 SMSs, Country Code: +55 (Brasil)

python3 bomber.py <TARGET>

# Custom SMS count and proxy.

python3 bomber.py --num 1000 --proxy <TARGET>

python3 bomber.py -N 1000 -P <TARGET>

# Custom API config file and proxy.

python3 bomber.py --config-path "./config.json" --proxy <TARGET>

python3 bomber.py -c "./config.json" -P <TARGET>

# Here's how you use all possible parameters to your taste.

python3 bomber.py --proxy --num 500 --country 55 --timeout 20 <TARGET>

python3 bomber.py -p -N 500 -c 55 -T 30 -t 20 <TARGET>

```

## Licenses
This project is licensed under the [GNU General Public License v3.0]

## THANKS

[THANK YOU ALL, AND A SAVE TO MY FRIEND NEXUSFIRE]
