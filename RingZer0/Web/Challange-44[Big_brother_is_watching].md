# Big brother is watching:
##  Even Google cannot find this one

This is basic web challange
From the clue *Even Google cannot find this one* , we conclude that we should  find something even google cant find. 
Google uses spiders to crawl websites in the internet, it uses some defined rule set to index and not to index particular pages in the internet
The rule set is _robots.txt_ rules , marking `Disallow:URL` in robots.txt says google not to index and display in the search results.

### Steps to capture the flag:
1. look at the robots.txt file in https://ringzer0team.com/robots.txt
1. You get `User-agent: *
Disallow: /16bfff59f7e8343a2643bdc2ee76b2dc/`
1. Going to the above URl https://ringzer0team.com/16bfff59f7e8343a2643bdc2ee76b2dc/
1. YUP...flag is here..:D

