# Muledump 2
Electric Boogaloo



Installation
===

To install this Muledump, firstly download Muledump from [here](https://github.com/killring/muledump), and download Muleproxy from [here](https://github.com/killring/muleproxy). Also, download GoLang from [here](https://golang.org/dl/) if you haven't already.

To run Muledump on your computer and NOT on a webserver, put your Muledump files into a folder somewhere. Put the contents of Muleproxy in your Muledump directory (IN the folder with `muledump.html`). Then, from the command line, use `go build` on `main.go`. Next, configure your Muledump as normal but do not put your password in `accounts_sample.js`. Remember to ADD YOUR EMAIL to `accounts_sample.js` and rename `accounts_sample.js` to `accounts.js`.

Then, configure Muleproxy. The example_config.json is simple to understand, just put your emails and passwords in there. Be sure to properly escape apostraphes and quotation marks in your passwords and emails by putting \ before them. Rename example_config.json to config.json. Finally, start Muleproxy with `proxy.exe "config.json` for Windows. Lastly, go to http://localhost:5353/muledump.html in your browser.

Congratulations, you've finally installed Muledump 2!

If you are not on Windows, please contact articun0z#1434 on Discord.

Issues
===
If you have an issue, please contact either articun0z#1434 on Discord, or add an Issue to this repo. **DO NOT** add issues to killring/muleproxy or killring/muledump. They **will not be read.**
