![](https://i.imgur.com/NGJJKnW.png)
*passapaˈrɔla * ● *order passed by word of mouth*

----------
## What is Passaparola ##
Passaparola is a proxy server for the Pebble speech recognition. 

Passaparola aims to fiddle between the main Pebble app and the [Nuance](https://www.nuance.com/) servers by changing the API key on the fly. 
Nuance [pricing](https://developer.nuance.com/public/index.php?task=memberServices) is proibitive for a community, the free tier can handle 20.000 requests per month, more than enough for a single user.

## TODO ##

 1. Understand the requests between *the* Pebble and Nuance (MITM)
 2. Build an app that can listen and reply the STT *(speech to text)* requests (probably using [CherryPy](http://cherrypy.org/)). 
