# webx
A powerful heuristic crawler for security engineer

## 

```
Usage of ./webx:
  -cookie string
        Cookie string.Format[domain;;cookie string] or [cookie string]. eg1. 163.com;; PHPSESSID=123456789  eg2. PHPSESSID=123456789
  -cookiefile string
        Cookie file, domain;;cookie string. eg. 163.com;;PHPSESSID=123456789 .   You can also set cookie_file in the config file!
  -d    Debug mode
  -domainblacklist string
        Domain blacklist file (default "domainblacklist.txt")
  -l string
        File containing urls to crawl
  -ma int
        Max concurrency agents. default is 1[configure file]
  -mb int
        Number of concurrent browser for crawling. default is 5[configure file]
  -mc int
        Max number of urls to crawl. default value see webxconfig.yaml
  -rf string
        Report format. default is html set in webxconfig.yaml
  -rod string
        Set the default value of options used by rod.
  -timeout int
        Minutes to wait before timing out a task. default is 3 hours
  -to string
        Push to proxy address(like xray).You can also set to_proxy_addr in the config file!
  -u string
        URL to crawl
  -v    Show Verbose output
```



