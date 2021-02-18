# camelboy

CamelBoy must be a runtime java library which builds apache camel routes as graph. I knew only one really useful solution - hawt.io, it's build over JMX. It's really good, builds actual routes map basing on heap but it works slow if there are a lot of routes and beans in your application. 

So, using NIH-principle as motivation I'm starting development of another one camel context parser with ability to avoid whole context parsing.

Objectives:
* memory economy
* fast response time
* adoptive visual design
* interactive routes graph
