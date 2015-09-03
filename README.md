# Awesome JSON Datasets
A curated list of awesome JSON datasets that don't require authentication.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard) [![Build Status](https://travis-ci.org/jdorfman/Awesome-JSON-Datasets.svg?branch=master)](https://travis-ci.org/jdorfman/Awesome-JSON-Datasets)

## TOC
* [Bitcoin](#bitcoin)
* [Cars](#cars)
* [Crime](#crime)
* [Currency](#currency)
* [GitHub API](#github-api)
* [Node.js API](#nodejs-api)
* [Reddit](#reddit)
* [TV Shows](#tv-shows)
* [Weather](#weather)
* [More Awesome Lists](#more-awesome-lists)
* [Contributing](#contributing)
* [License](#license)

## Bitcoin
* [Latest Block](https://blockchain.info/latestblock)
* [Unconfirmed Transactions](https://blockchain.info/unconfirmed-transactions?format=json)

> Pro Tip: Check out [Blockchain Data API](https://blockchain.info/api/blockchain_api) for more options.

* [Global Tickers](https://api.bitcoinaverage.com/ticker/global/)
  * [All](https://api.bitcoinaverage.com/ticker/global/all)
  * [USD](https://api.bitcoinaverage.com/ticker/global/USD/)
  * [GBP](https://api.bitcoinaverage.com/ticker/global/GBP/)
  * [EUR](https://api.bitcoinaverage.com/ticker/global/EUR/)
  * [INR](https://api.bitcoinaverage.com/ticker/global/INR/)
  * [AUD](https://api.bitcoinaverage.com/ticker/global/AUD/)
  * [CAD](https://api.bitcoinaverage.com/ticker/global/CAD/)
  * [JPY](https://api.bitcoinaverage.com/ticker/global/JPY/)
  * [CNY](https://api.bitcoinaverage.com/ticker/global/CNY/)

> Pro Tip: Currencies dedicated endpoints are available at `https://api.bitcoinaverage.com/ticker/global/ENTER-SYMBOL/`

## Cars
* [All Makes](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes)
* Makes Sold in USA
  * [1940](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes&year=1941&sold_in_us=1)
  * [1950](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes&year=1950&sold_in_us=1)
  * [1960](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes&year=1960&sold_in_us=1)
  * [1970](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes&year=1970&sold_in_us=1)
  * [1980](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes&year=1980&sold_in_us=1)
  * [1990](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes&year=1990&sold_in_us=1)
  * [2000](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes&year=2000&sold_in_us=1)
  * [2010](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getMakes&year=2010&sold_in_us=1)

> Pro Tip: replace the field-value for a year not listed e.g. `?&cmd=getMakes&year=1969`.
You can also change the country e.g. `sold_in_uk=1`, `sold_in_de=1`, etc.

* Models
  * [Ford](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=ford)
  * [GMC](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=gmc)
  * [Acura](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=acura)
  * [Cadillac](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=Cadillac)
  * [Ferrari](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=Ferrari)
  * [Jaguar](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=Jaguar)
  * [Mercedes-Benz](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=Mercedes-Benz)
  * [BMW](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=BMW)
  * [Nissan](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=Nissan)
  * [Porsche](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=Porsche)
  * [Subaru](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=Subaru)
  * [Toyota](http://www.carqueryapi.com/api/0.3/?callback=?&cmd=getModels&make=Toyota)

> Pro Tip: replace the field-value for a model not listed e.g. `make=CarCompany`.

## Crime

* [DATA.POLICE.UK](https://data.police.uk/docs/)
  * [Crimes at Location](https://data.police.uk/api/crimes-at-location?date=2015-02&lat=52.629729&lng=-1.131592)
  * [Street Crime Dates](https://data.police.uk/api/crimes-street-dates)
  * [Neighbourhoods](https://data.police.uk/api/leicestershire/neighbourhoods)
  * [List of Forces](https://data.police.uk/api/forces)
    * [Leicestershire Police](https://data.police.uk/api/forces/leicestershire)
    * [Bedfordshire Police](https://data.police.uk/api/forces/bedfordshire)
    * [Cleveland Police](https://data.police.uk/api/forces/cleveland)
    * [City of London Police](https://data.police.uk/api/forces/city-of-london)
    * [Dorset Police](https://data.police.uk/api/forces/dorset)
    * [Devon & Cornwall Police](https://data.police.uk/api/forces/devon-and-cornwall)
    * [Dyfed-Powys Police](https://data.police.uk/api/forces/dyfed-powys)
    * [Essex Police](https://data.police.uk/api/forces/essex)
    * [Greater Manchester Police](https://data.police.uk/api/forces/greater-manchester)
    * [Gwent Police](https://data.police.uk/api/forces/gwent)
    * [Humberside Police](https://data.police.uk/api/forces/humberside)
    * [Kent Police](https://data.police.uk/api/forces/kent)
    * [Leicestershire Police](https://data.police.uk/api/forces/leicestershire)
    * [Lincolnshire Police](https://data.police.uk/api/forces/lincolnshire)
    * [Merseyside Police](https://data.police.uk/api/forces/merseyside)
    * [Metropolitan Police Service](https://data.police.uk/api/forces/metropolitan)
    * [North Wales Police](https://data.police.uk/api/forces/north-wales)
    * [North Yorkshire Police](https://data.police.uk/api/forces/north-yorkshire)
    * [Northamptonshire Police](https://data.police.uk/api/forces/northamptonshire)
    * [Northumbria Police](https://data.police.uk/api/forces/northumbria)
    * [Nottinghamshire Police](https://data.police.uk/api/forces/nottinghamshire)
    * [Police Service of Northern Ireland](https://data.police.uk/api/forces/northern-ireland)
    * [South Wales Police](https://data.police.uk/api/forces/south-wales)
    * [South Yorkshire Police](https://data.police.uk/api/forces/south-yorkshire)
    * [Staffordshire Police](https://data.police.uk/api/forces/staffordshire)
    * [Surrey Police](https://data.police.uk/api/forces/surrey)
    * [Sussex Police](https://data.police.uk/api/forces/sussex)
    * [Thames Valley Police](https://data.police.uk/api/forces/thames-valley)
    * [Warwickshire Police](https://data.police.uk/api/forces/warwickshire)
    * [West Mercia Police](https://data.police.uk/api/forces/west-mercia)
    * [West Midlands Police](https://data.police.uk/api/forces/west-midlands)
    * [West Yorkshire Police](https://data.police.uk/api/forces/west-yorkshire)
    * [Wiltshire Police](https://data.police.uk/api/forces/wiltshire)
    * [Avon and Somerset Constabulary](https://data.police.uk/api/forces/avon-and-somerset)
    * [Cambridgeshire Constabulary](https://data.police.uk/api/forces/cambridgeshire)
    * [Cheshire Constabulary](https://data.police.uk/api/forces/cheshire)
    * [Cumbria Constabulary](https://data.police.uk/api/forces/cumbria)
    * [Derbyshire Constabulary](https://data.police.uk/api/forces/derbyshire)
    * [Durham Constabulary](https://data.police.uk/api/forces/durham)
    * [Gloucestershire Constabulary](https://data.police.uk/api/forces/gloucestershire)
    * [Hampshire Constabulary](https://data.police.uk/api/forces/hampshire)
    * [Hertfordshire Constabulary](https://data.police.uk/api/forces/hertfordshire)
    * [Lancashire Constabulary](https://data.police.uk/api/forces/lancashire)
    * [Norfolk Constabulary](https://data.police.uk/api/forces/norfolk)
    * [Suffolk Constabulary](https://data.police.uk/api/forces/suffolk)

## Currency

* [Latest Foreign Exchange Rates](http://api.fixer.io/latest)
  * [USD](http://api.fixer.io/latest?base=USD)
  * [AUD](http://api.fixer.io/latest?base=AUD)
  * [BGN](http://api.fixer.io/latest?base=BGN)
  * [BRL](http://api.fixer.io/latest?base=BRL)
  * [CAD](http://api.fixer.io/latest?base=CAD)
  * [CHF](http://api.fixer.io/latest?base=CHF)
  * [CNY](http://api.fixer.io/latest?base=CNY)
  * [CZY](http://api.fixer.io/latest?base=CZK)
  * [DKK](http://api.fixer.io/latest?base=DKK)
  * [GBP](http://api.fixer.io/latest?base=GBP)
  * [HKD](http://api.fixer.io/latest?base=HKD)
  * [HRK](http://api.fixer.io/latest?base=HRK)
  * [HUF](http://api.fixer.io/latest?base=HUF)
  * [IDR](http://api.fixer.io/latest?base=IDR)
  * [ILS](http://api.fixer.io/latest?base=ILS)
  * [INR](http://api.fixer.io/latest?base=INR)
  * [JPY](http://api.fixer.io/latest?base=JPY)
  * [KRW](http://api.fixer.io/latest?base=KRW)
  * [MXN](http://api.fixer.io/latest?base=MXN)
  * [MYR](http://api.fixer.io/latest?base=MYR)
  * [NOK](http://api.fixer.io/latest?base=NOK)
  * [NZD](http://api.fixer.io/latest?base=NZD)
  * [PHP](http://api.fixer.io/latest?base=PHP)
  * [PLN](http://api.fixer.io/latest?base=PLN)
  * [RON](http://api.fixer.io/latest?base=RON)
  * [RUB](http://api.fixer.io/latest?base=RUB)
  * [SEK](http://api.fixer.io/latest?base=SEK)
  * [SGD](http://api.fixer.io/latest?base=SGD)
  * [THB](http://api.fixer.io/latest?base=THB)
  * [TRY](http://api.fixer.io/latest?base=TRY)
  * [ZAR](http://api.fixer.io/latest?base=ZAR)
  * [EUR](http://api.fixer.io/latest?base=EUR)
* [Compare Foreign Exchange Rates](http://api.fixer.io/latest?symbols=USD,GBP) *(Replace `USD,GBP` with `symbols` you want to compare.)*
* [Historical Foreign Exchange Rates](http://api.fixer.io/2000-01-03) *(Replace `2000-01-03` with another date.)*
* [VAT rates for EU](http://jsonvat.com/)

## GitHub API
* [Emojis](https://api.github.com/emojis)
* [Events](https://api.github.com/events)
* [Gists](https://api.github.com/gists)

## Node.js API
* [console](https://nodejs.org/api/console.json)
* [Crypto](https://nodejs.org/api/crypto.json)
* [Debugger](https://nodejs.org/api/debugger.json)
* [DNS](https://nodejs.org/api/dns.json)
* [Domain](https://nodejs.org/api/domain.json)
* [Events](https://nodejs.org/api/events.json)
* [File System](https://nodejs.org/api/fs.json)
* [global](https://nodejs.org/api/globals.json)
* [HTTP](https://nodejs.org/api/http.json)
* [HTTPS](https://nodejs.org/api/https.json)
* [Modules](https://nodejs.org/api/modules.json)
* [net](https://nodejs.org/api/net.json)
* [os](https://nodejs.org/api/os.json)
* [Path](https://nodejs.org/api/path.json)
* [process](https://nodejs.org/api/process.json)
* [punycode](https://nodejs.org/api/punycode.json)
* [Query String](https://nodejs.org/api/querystring.json)
* [Readline](https://nodejs.org/api/readline.json)
* [REPL](https://nodejs.org/api/repl.json)
* [Smalloc](https://nodejs.org/api/smalloc.json)
* [Stream](https://nodejs.org/api/stream.json)
* [StringDecoder](https://nodejs.org/api/string_decoder.json)
* [Timers](https://nodejs.org/api/timers.json)
* [TLS (SSL)](https://nodejs.org/api/tls.json)
* [TTY](https://nodejs.org/api/tty.json)
* [UDP / Datagram Sockets](https://nodejs.org/api/dgram.json)
* [URL](https://nodejs.org/api/url.json)
* [util](https://nodejs.org/api/util.json)
* [Executing JavaScript](https://nodejs.org/api/vm.json)
* [Zlib](https://nodejs.org/api/zlib.json)
* [Assert](https://nodejs.org/api/assert.json)
* [Buffer](https://nodejs.org/api/buffer.json)
* [Addons](https://nodejs.org/api/addons.json)
* [Child Process](https://nodejs.org/api/child_process.json)
* [Cluster](https://nodejs.org/api/cluster.json)

## Reddit
* [/r/all](http://www.reddit.com/r/all.json)
* [/r/AskReddit](https://www.reddit.com/r/AskReddit.json)
* [/r/funny](https://www.reddit.com/r/funny.json)
* [/r/pics](https://www.reddit.com/r/pics.json)
* [/r/todayilearned](https://www.reddit.com/r/todayilearned.json)
* [/r/announcements](https://www.reddit.com/r/announcements.json)
* [/r/worldnews](https://www.reddit.com/r/worldnews.json)
* [/r/science](https://www.reddit.com/r/science.json)
* [/r/IAmA](https://www.reddit.com/r/IAmA.json)
* [/r/videos](https://www.reddit.com/r/videos.json)
* [/r/gaming](https://www.reddit.com/r/gaming.json)

> Pro Tip: you can append `.json` to any subreddit url.

## TV Shows
* [Girls (HBO)](http://api.tvmaze.com/singlesearch/shows?q=hbo&embed=episodes)
* [Dexter (Showtime)](http://api.tvmaze.com/singlesearch/shows?q=dexter&embed=episodes)
* [Shameless (Showtime)](http://api.tvmaze.com/singlesearch/shows?q=shameless&embed=episodes)
* [Mr. Robot (USA)](http://api.tvmaze.com/singlesearch/shows?q=mr-robot&embed=episodes)
* [Ray Donovan (Showtime)](http://api.tvmaze.com/singlesearch/shows?q=Ray-Donovan&embed=episodes)
* [Better Call Saul (AMC)](http://api.tvmaze.com/singlesearch/shows?q=better-call-saul&embed=episodes)
* [Homeland (Showtime)](http://api.tvmaze.com/singlesearch/shows?q=Homeland&embed=episodes)
* [Silicon Valley (HBO)](http://api.tvmaze.com/singlesearch/shows?q=silicon-valley&embed=episodes)
* [Breaking Bad (AMC)](http://api.tvmaze.com/singlesearch/shows?q=breaking-bad&embed=episodes)
* [The Walking Dead (AMC)](http://api.tvmaze.com/singlesearch/shows?q=the-walking-dead&embed=episodes)
* [South Park (Comedy Central)](http://api.tvmaze.com/singlesearch/shows?q=south-park&embed=episodes)
* [Futurama (Comedy Central)](http://api.tvmaze.com/singlesearch/shows?q=Futurama&embed=episodes)

> Pro Tip: replace the field-value for a show not listed e.g. `shows?q=show-name`. More options [here](http://www.tvmaze.com/api)

## Weather
* [Los Angeles](http://api.openweathermap.org/data/2.5/weather?q=Los_Angeles)
* [New York](http://api.openweathermap.org/data/2.5/weather?q=New_York)
* [Atlanta](http://api.openweathermap.org/data/2.5/weather?q=Atlanta)
* [Chicago](http://api.openweathermap.org/data/2.5/weather?q=chicago)
* [Miami](http://api.openweathermap.org/data/2.5/weather?q=miami)
* [San Francisco](http://api.openweathermap.org/data/2.5/weather?q=San_Francisco)
* [Charleston](http://api.openweathermap.org/data/2.5/weather?q=Charleston)
* [Las Vegas](http://api.openweathermap.org/data/2.5/weather?q=Las_Vegas)
* [Seattle](http://api.openweathermap.org/data/2.5/weather?q=Seattle)
* [Washington DC](http://api.openweathermap.org/data/2.5/weather?q=Washington_DC)
* [New Orleans](http://api.openweathermap.org/data/2.5/weather?q=New_Orleans)
* [Louisville](http://api.openweathermap.org/data/2.5/weather?q=Louisville)
* [Portland](http://api.openweathermap.org/data/2.5/weather?q=Portland)
* [Ashburn](http://api.openweathermap.org/data/2.5/weather?q=Ashburn)
* [Nashville](http://api.openweathermap.org/data/2.5/weather?q=Nashville)
* [Austin](http://api.openweathermap.org/data/2.5/weather?q=Austin)
* [Saint Louis](http://api.openweathermap.org/data/2.5/weather?q=Saint_Louis)
* [Sedona](http://api.openweathermap.org/data/2.5/weather?q=Sedona)
* [Honolulu](http://api.openweathermap.org/data/2.5/weather?q=Honolulu)
* [Branson](http://api.openweathermap.org/data/2.5/weather?q=Branson)
* [Boston](http://api.openweathermap.org/data/2.5/weather?q=Boston)
* [Savannah](http://api.openweathermap.org/data/2.5/weather?q=Savannah)
* [Orlando](http://api.openweathermap.org/data/2.5/weather?q=Orlando)
* [Lahaina](http://api.openweathermap.org/data/2.5/weather?q=Lahaina)
* [Saint Augustine](http://api.openweathermap.org/data/2.5/weather?q=Saint_Augustine)
* [San Antonio](http://api.openweathermap.org/data/2.5/weather?q=San_Antonio)
* [Dallas](http://api.openweathermap.org/data/2.5/weather?q=Dallas)

> Pro Tip: replace the field-value for a city not listed e.g. `weather?q=city_name`.

## More Awesome Lists
* [Awesome](https://github.com/sindresorhus/awesome) *(The OG List)*
* [JSON](https://github.com/burningtree/awesome-json) (Libraries and Resources)
* [WPO](https://github.com/davidsonfellipe/awesome-wpo) *(Web Performance Optimization)*
* [Shell](https://github.com/alebcay/awesome-shell) *(CLI Frameworks, Toolkits and Guides)*

## Contributing
If you want to contribute, please read the [contribution guidelines](CONTRIBUTING.md).

## License
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [MaxCDN](https://www.maxcdn.com) has waived all copyright and related or neighboring rights to this work.
