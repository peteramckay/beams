#Beams v0.2.x (Beta)

###An operating system for news

Beams is an open full-stack framework for building media websites, including news sites, blogs, video apps, et cetera. This is a development branch of the software, forked from the latest public release version maintained by Roscoe Labs at https://github.com/roscoelabs

Beams includes the following features:

- **Secure server using Nginx and Node.js.** A simple, fast server script to get your project up and running quickly using HTTPS. A basic website file structure is also included for serving static pages of content.

- **Ultraresponsive layout.** Layout is based on a 20-column, 4,000-pixel grid. This allows elegant resizing of elements on any size screen, from a large TV down to a smartphone. Video players are also responsive, including support for embedded players for YouTube, Vimeo, and self-hosted HTML5 video.

- **Default typefaces from Google Fonts.** We use Merriweather for headlines and Open Sans for pretty much everything else. (Of course, implementers should feel free to change these to something else if your project requires.)

- **jQuery 2.1.4.** The framework's `beams-client.min.js` file includes a full, minified copy of this popular JavaScript library so your project can quickly call functions from it.

###Requirements

To implement Beams, you'll need a computer to use as a server that has the following installed:

- **A valid SSL certificate.** You'll have to buy one of these from a certificate authority like Comodo, DigiCert, etc. Be sure to follow the issuer's install instructions carefully.

- **Nginx v1.7.11 or later.** This part of the stack handles HTTPS verification and, if your project calls for it, enhancfed load balancing to handle heavy traffic.

- **Node.js 0.10.38 or later.** Popular server-side JavaScript platform that uses Google's V8 engine.

- **npm 1.4.28 or later.** The node package manager. Helps add modules that enhance functionality of the stock version of Node.js.

- **Express 4.12.3 or later.** Add-on Node.js module for building full-featured Web apps.

- **Forever 0.14.1 or later.** Add-on Node.js module that keeps the server running persistently.

- **MongoDB v3.0.1 or later.** A document-oriented NoSQL database.

- **Mongoskin v1.4.13 or later.** Node.js plugin/driver to aid integration with MongoDB.

For full installation and usage instructions, see the "Getting Started" guide the Beams community maintains on GitHub at http://bit.ly/1JPRIjJ

Cheers,

Peter McKay  
Twitter: @peteramckay  
