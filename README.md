<!---Copyright 2017 Nirmal Kumar--->

<!---This file is part of LibreRead.--->

<!---LibreRead is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.--->

<!---LibreRead is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.--->

<!---You should have received a copy of the GNU General Public License
along with LibreRead.  If not, see <http://www.gnu.org/licenses/>.--->

# LibreRead [![Build Status](https://api.travis-ci.org/LibreRead/LibreRead.svg?branch=master)](https://travis-ci.org/LibreRead/LibreRead)
Self-hosted Free(Libre) Ebook Reader. https://libreread.org

![Alt text](/static/img/screenshot.png?raw=true "Home Page")

### Features
 - Easy installation
 - Built using Golang
 - Browser-based
 - Responsive design
 - Full-text search
 - Highlight & Annotate
 - Supports PDF & EPUB
 
### Production setup
Please check [this guide](https://github.com/LibreRead/server/blob/master/docs/INSTALL.md)

### Development setup
Install redis and optionally elasticsearch. if you want to use elasticsearch, do `export LIBREREAD_ELASTICSEARCH=1` and run the following commands.
 - `go get -d github.com/LibreRead/server/cmd/libreread`
 - `cd $GOPATH/src/github.com/LibreRead/server`
 - `go run ./cmd/libreread/main.go`
 
 This will run the app on `localhost:8080`

### Supported by
<img src="https://www.digitalocean.com/assets/media/logos-badges/png/DO_Logo_Horizontal_Black-a93a7c21.png" height="40px" alt="Supported by Digital Ocean" />

If you find LibreRead useful, you could support our development by either making an [one-time donation](https://www.paypal.me/paynirmal) or by [becoming a patron](https://www.patreon.com/mysticmode). Thank you! 😍
