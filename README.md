# Hugo Start

A simple hugo boilerplate showing some of Hugo's functionality.


## Quick Start

- Download [latest release](rel) and unzip into your working directory. 
- Rename the folder as you want.
- Navigate to this folder in your command line (PowerShell in Windows, Terminal in macOS or Linux).
- Run `hugo server`. 
- Hugo should return several messages (see code below). There is an address that allows opening the website in your browser: below it's `http://localhost:1313/hugo-start/`.

```
$ hugo server

                   | EN  
+------------------+----+
  Pages            | 21  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     |  2  
  Processed images |  0  
  Aliases          |  0  
  Sitemaps         |  1  
  Cleaned          |  0  

Total in 30 ms
Watching for changes in /Users/<username>/Projects/start/{content,data,layouts,static}
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at http://localhost:1313/hugo-start/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```

## Best Practice

When adding small changes, do not commit anything from `/docs folder`. Push changes in docs only after some milestone, preferably by a single user, so that merge conflicts do not make work with the repository difficult.

Generally, built files are not to be commited exactly for this reason — but in this case, they're useful to generate a [Github Sites based website](http://jan-martinek.github.io/hugo-start/).


## Troubleshooting

- When running `hugo new`, this error is shown: **Unable to locate Config file. Perhaps you need to create a new site.** You're in a wrong folder.
- When running any comman, this error is shown: **command not found: hugo**. Hugo is not installed correctly. Either reinstall Hugo or check whether you typed it correctly.


[rel]: https://github.com/jan-martinek/hugo-start/releases
