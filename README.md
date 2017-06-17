 <pre>
    

████████╗ ██████╗ ██████╗     ██████╗  ██████╗ ████████╗    
╚══██╔══╝██╔═══██╗██╔══██╗    ██╔══██╗██╔═████╗╚══██╔══╝    
   ██║   ██║   ██║██████╔╝    ██████╔╝██║██╔██║   ██║       
   ██║   ██║   ██║██╔══██╗    ██╔══██╗████╔╝██║   ██║       
   ██║   ╚██████╔╝██║  ██║    ██████╔╝╚██████╔╝   ██║       
   ╚═╝    ╚═════╝ ╚═╝  ╚═╝    ╚═════╝  ╚═════╝    ╚═╝       
                                                            

                                       
                    `.` `     
                ``.:.--.`     
               .-+++/-`       
              `+sso:`         
           `` /yy+.           
           -+.oho.            
            o../+y            
           -s.-/:y:`          
        .:o+-`--::oo/-`       
     `/o+:.```---///oss+-     
   .+o:.``...`-::-+++++sys-   
  :y/```....``--::-yooooosh+  
 -h-``--.```..-:-::ssssssssd+ 
 h:``:.``....`--:-++hsssyyyym.
.d.`/.``--.```:--//odyyyyyyym/
`d.`+``:.```.--/-+/smyyhhhhhm:
 os`./`/````/`-/:+oydhhhhhhdh`
 `so.-/-:``./`.//osmddddddmd. 
   /s/-/:/.`/..+/ydmdddddmo`  
    `:oosso/:+/syNmddmdy/.    
        `-/++oosyso+/.`      




██████╗ ███████╗██████╗ ███████╗██████╗  ██████╗    ██╗███╗   ██╗███████╗██╗██████╗ ███████╗
██╔══██╗██╔════╝██╔══██╗██╔════╝╚════██╗██╔════╝    ██║████╗  ██║██╔════╝██║██╔══██╗██╔════╝
 ██║  ██║█████╗  ██║  ██║███████╗ █████╔╝██║         ██║██╔██╗ ██║███████╗██║██║  ██║█████╗  
██║  ██║██╔══╝  ██║  ██║╚════██║ ╚═══██╗██║         ██║██║╚██╗██║╚════██║██║██║  ██║██╔══╝  
██████╔╝███████╗██████╔╝███████║██████╔╝╚██████╗    ██║██║ ╚████║███████║██║██████╔╝███████╗
╚═════╝ ╚══════╝╚═════╝ ╚══════╝╚═════╝  ╚═════╝    ╚═╝╚═╝  ╚═══╝╚══════╝╚═╝╚═════╝ ╚══════╝
                                                                                            


</pre>

## A python web crawler for Deep and Dark Web.

### Working Procedure/Basic Plan
The basic procedure executed by the web crawling algorithm takes a list of seed URLs as its input and repeatedly executes
the following steps:

1. Remove a URL from the URL list.
2. Check existence of the page.
3. Download the corresponding page.
4. Check the Relevancy of the page.
5. Extract any links contained in it.
6. Check the cache if the links are already in it.
7. Add the unique links back to the URL list.
8. After all URLs are processed, return the most relevant page.

### Features
1. Crawls Tor links (.onion) only.
2. Returns Page title and address.
3. Cache links so that there won't be duplicate links.
...(will be updated)

## Contribute
Contributions to this project are always welcome. 
To add a new feature fork this repository and give a pull request when your new feature is tested and complete.
The branch name should be your new feature name in the format <Feature_feature_name>. For example, <i>Feature_FasterCrawl_1.0</i>.
Contributor name will be updated to the below list. :D

## Dependencies 
1. Tor 
2. Python 3.x (Make sure pip3 is there)
3. Python Stem Module
4. urllib
5. Beautiful Soup 4


### Have ideas?
If you have new ideas which is worth implementing, mention those by starting a new issue with the title [FEATURE_REQUEST].
If the idea is worth implementing, congratz you are now a contributor.

## CREDITS

- [X] P5N4PPZ - Owner
- [X] @agrepravin - Contributor
