```
 _______  _____         _____ _______ _____ __   _ ______  _______  ______
 |______ |   __| |        |   |______   |   | \  | |     \ |______ |_____/
 ______| |____\| |_____ __|__ |       __|__ |  \_| |_____/ |______ |    \_
                                                                          
```
<br>
SQLI Finder ( GO edition ) is a very simple SQLI Ajax crawler and SQL injection scanner re written and mind mapped from the original sqlifinder which is seen here https://github.com/americo/sqlifinder
<br>

# what is so special about this remake 
```
To give you a general idea of why i even remade this when it was made, at first it was a test for my skills i figured why not see my max strength in GoLang right

now and turns out i exceeded them, but then i noticed in the og scanner its just a simple listed scanner if that and crawler, it crawls a url off the target then scans tht target and continues until it hits a dead end, the issue with alot of development scripts like this is they cause a whole lot of- say unneeded noise that 

can get a person caught, so i decided to add some tor projection when constantly making requests to crawl the links, added tor socket/node changing, added tor stats, then added options where you can SQL inject every URL in a given list and keep testing and testing until well you run out. i will be honest this is not the 

most accurate but it is still some improovement to the og project, i also added signal handelers, connection testers, tor socket testers, individual scanning, a faster spider, sleep methods so tor doesnt time out on making requests etc etc and a bit more error handeling.
```
