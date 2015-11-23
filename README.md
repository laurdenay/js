[Turtl](https://turtl.it/)
==========================

This is the heart of Turtl!

It's the javascript core that runs the app whether on desktop or mobile. It
contains Turtl's interfaces, logic, crypto, etc.

## Building

Turtl uses a makefile to generate itself. Here's a fw commands to get you started
(this assumed you have Node.js/npm installed already):

```bash
mkdir turtl
cd turtl/
git clone https://github.com/turtl/js.git
cd js/
npm install
make
```

Running `make` here generates all the assets for the project and it's now ready
to be run by any webserver (just make sure all requests are send to index.html,
see the .htaccess file for reference).

