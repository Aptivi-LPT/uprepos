# uprepos

uprepos is a very small script that lets you update all your repositories found under a folder containing all your Git repositories.

## Usage

```shell
uprepos MyRepos
```

## How to install

It can be installed either locally on your home directory or system-wide.

### cURL

* Local install

```shell
curl -fsSL https://raw.githubusercontent.com/Aptivi/uprepos/main/uprepos > $HOME/uprepos
chmod +x $HOME/uprepos
```

* System-wide install

```shell
curl -fsSL https://raw.githubusercontent.com/Aptivi/uprepos/main/uprepos | sudo tee /usr/local/bin/uprepos
sudo chmod +x /usr/local/bin/uprepos
```

### WGet

* Local install

```shell
wget -O$HOME/uprepos https://raw.githubusercontent.com/Aptivi/uprepos/main/uprepos
chmod +x $HOME/uprepos
```

* System-wide install

```shell
sudo wget -O/usr/local/bin/uprepos https://raw.githubusercontent.com/Aptivi/uprepos/main/uprepos
sudo chmod +x /usr/local/bin/uprepos
```

## Features

* Update all your repositories in one go. No more switching current directories and repeating commands.

## License

```
MIT License

Copyright (c) 2022 Aptivi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

