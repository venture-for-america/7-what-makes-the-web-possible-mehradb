# What makes the web possible
To make the web work we need:

1. a common language (HTML)
2. a way to serve content (Web servers)
3. a way to view content (Web browsers)
4. servers and browsers should have an agreed-upon way of exchanging data (HTTP)
5. a way to send HTTP request to any computer connected to a network (The Internet)

Let's start with the last item. If we had all the other components, but we did not have a way for browsers
to find servers or for servers to return HTML texts to browsers, there would be no Web. The web stands on the shoulders of a giant. That giant is the Internet. The Internet provides addresses to the clients and servers so that they can exchange information. It also provides the error-correction and reconnection rules (How does the browser know to ask for more data once you get out from underneath a tunnel?).

On top of this address and connection platform, servers and clients exchange information ("the web"). Technologists say that **the web is an Internet application**, but it is not the only one. Just as the address scheme for houses and the roadways can be used to deliver packages or bills, another **application** of post code addressing and roadways is "delivering a pizza." Another **application** is "organizing precincts for voting." Applications work "on top" of lower level constructs.

Now that we have a way to exchange HTTP requests (web requests), what are the other components for?

Let start with HTML. It's the language of the web. It's how we express information. Every website ever created is expressed using HTML. If we want to publish anything on the web, it will at some point be contained inside of an HTML document.

Once we have an HTML document we want to publish, where do we place it to make it available to billions of internet users? Web servers make our content available to everyone on the internet. Web servers are our content publishers (from a technical point of view).

Our content is now available to the whole web. Yay! What tool can we use to view it? How do we reach it? This is where web browsers come in. Web browsers know how to translate HTML code into something that is pleasant to read for a human.

How do web browsers and servers interact? We have an agreed-upon convention for servers and browsers to exchange data. That convention (standard) is HTTP, or, in networking parlance, a "network protocol." It's how web browsers speak to web servers and ask the servers to send them payloads of HTML. _Be careful_: HTTP is like a handshake and a request: "Ms. Server, please tell me what information you have in the file `poodles.html`." Ms. Server then sends it on, indifferent to the content inside the file. That's HTTP, the hyper-text transfer protocol, the rules for sending hyper-text, also known as HTML.

![HTTP Request / Response Diagram](https://curriculum-content.s3.amazonaws.com/fswb-assets/what-makes-the-web-possible/request_response.jpg)

_Extremely High-Resolution, Retina &reg;-Compatible Diagram of the HTTP request / response cycle_


At its core, these five components make the internet possible. To recap:

1. The internet allows browsers and servers to connect to each other.
2. Browsers and server interact with an agreed-upon protocol: HTTP.
3. Content is represented as HTML documents.
4. HTML documents are published by web servers.
5. HTML documents are viewed using web browsers.

The web and the internet are two marvelous pieces of engineering work, but that is not the reason why it’s hard to imagine our life without them today. Their inventors made them free for anyone to use. Creators are able to build on top of the web and internet and reach anyone. This is what makes the web and internet magical.

How can you be one of those creators? Simply know how to generate HTML!
