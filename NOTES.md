### Part 0: Fundamentals of web apps
1st rule of webdev: keep developer console open (F12 or inspect)  
it has lots of tabs, yet Console is most important  
[HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) protocol is used for client-server   communication  
use Network tab for that (Headers, Preview, Response etc)  

##### HTTP GET
for example [app](https://studies.cs.helsinki.fi/exampleapp/) chain of events starts when we open link:  
HTTP [GET](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET) ->   
<- HTML fetched  
HTTP GET due to \<img> tag ->   
<- image fetched  
[UML](https://www.geeksforgeeks.org/unified-modeling-language-uml-sequence-diagrams/) can be used for handy visuals  

HTML page begins to render before image fetched  
response headers tell browser what content type to render and some other info  
e.g. [Content-Type](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Type): [UTF-8](https://en.wikipedia.org/wiki/UTF-8) encoded   [HTML](https://en.wikipedia.org/wiki/HTML) page
[<head>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head) used for metadata and [<body>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body) for actual rendered content  
we get 200 OK [status code](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes) as one of [header fields](https://en.wikipedia.org/wiki/List_of_HTTP_header_fields)  
there are response as well as request headers  
Preview and Response used for preview and raw html/css/js/json [devtools reference](https://developer.chrome.com/docs/devtools/network/)  

---- 
[Overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)  
[Anatomy of HTTP request](https://gavilan.blog/2019/01/03/anatomy-of-an-http-request/)  
[Anatomy of HTTP request](https://betterprogramming.pub/the-anatomy-of-an-http-request-728a469ecba9)  
[Transaction in Node](https://nodejs.org/uk/docs/guides/anatomy-of-an-http-transaction/)  
[HTTP transaction in steps](https://www.catchpoint.com/blog/http-transaction-steps)  
[How HTTP request works](https://flaviocopes.com/http-request/)  
[Essay on HTTP](https://xeiaso.net/blog/how-http-requests-work-2020-05-19)  
[Made easy](http://ksuweb.kennesaw.edu/~bsetzer/old/4720sp16/nanoc/output/notes/supplement/HTTP%20Made%20Really%20Easy.html)  
[One more](https://cis.msjc.edu/Tutorials/Internet/WWW/HTTP/)  
[Web course CS142](https://web.stanford.edu/class/cs142/lectures.html)   
[How does the Internet works](http://www.theshulers.com/whitepapers/internet_whitepaper/index.html)  
[HTTP programming](https://cs.lmu.edu/~ray/notes/httpprogramming/)  
[Bunch of webdev courses](https://github.com/Developer-Y/cs-video-courses#web-programming-and-internet-technologies)  
[CS101](https://web.stanford.edu/class/cs101/index.html)  
[CIS 526](https://textbooks.cs.ksu.edu/cis526/)  
[In Racket](https://plt.cs.northwestern.edu/snapshots/current/doc/web-server/index.html)  
[CSE 154](https://courses.cs.washington.edu/courses/cse154/22su/resources/index.html)  
[OLD](https://courses.cs.washington.edu/courses/cse154/14au/lectures.shtml#today)  

----
- Browser knows type of data by HTML tags or it can sniff it sometimes?
- How server forms a response of file/document? Is it HTTP response with code and payload or not?


##### Traditional web application











