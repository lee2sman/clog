# clog
A blog that is read with curl!

This is an instance of an [idea](https://github.com/jameschip/clog) devised by [James Chip](https://www.jameschip.io/) to create a lightweight (in terms of bandwidth/software/lines of code) blog that you can access through running the ```curl``` command in a terminal. My web-based blog [Nosebook](http://leetusman.com/nosebook/) could be read in the terminal with Links, Lynx or [w3m](http://w3m.sourceforge.net/) for example, but, oh, what the hell, this is even simpler. No (text) browser needed.

[curl](https://curl.haxx.se/) (aka cURL) is a command-line tool to transfer data. It's used by iOT devices, servers, phones, cars, TVs, etc.

#### To access the index:

Run the following in your terminal (the -s is for *silent mode* so you don't see all the header cruft).

```
curl -s leetusman.com/clog/index
```

This will return a list of all clog posts you can read.

To access a specific post you can run 

```
curl -s leetusman.com/clog/<number id>
```

To see a list of other clogs (at the time I'm writing this there are 3!), you can visit a clog ring page here in your browser: [https://www.jameschip.io/clogs/](https://www.jameschip.io/clogs/)
