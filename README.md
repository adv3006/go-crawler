# Go-Crawler
A Golang [CLI](https://en.wikipedia.org/wiki/Command-line_interface) application that generates an "internal links" report for any website on the internet by [crawling](https://www.cloudflare.com/learning/bots/what-is-a-web-crawler/) each page of the site.

## How to use
    # build to the binary
    go build -o crawler
    
    # usage: ./crawler URL maxConcurrency maxPages
    ./crawler "https://example.com" 3 10