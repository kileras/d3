# D3 fork with no global by default

This is just a fork of D3 (https://github.com/mbostock/d3) and it will have the same functionality that d3 has, the only change is the fact that if you load d3.js directly and you have a module system in place it won't create the global d3 object. You can still get the global d3 if you load it throught index.js, that now is the responsible of exposing it to the global context. Also there is a second change which is that the jsdom dependency has been removed to make it easier to use in a windows environment.
