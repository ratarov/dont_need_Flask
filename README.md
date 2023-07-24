# Don't_need_Flask
Low level web-app without web-frameworks

## What is it for?
Just trying to understand what are sockets and how web-apps work without frameworks' magic.


Thanks to Oleg Molchanov for great lesson.

## Content
Small web-app with 2 endpoints (main & /blog) responding with html-templates.
- creates server-socket
- parses incoming request
- checks available endpoints
- returns html for available endpoints with status 200; 404 if endpoint is not available, 405 for unsupported methods (all except GET)