A folk version of GMaps.js which to support RequireJS
=========================================================

It's based on [GMaps.js](http://hpneo.github.com/gmaps/) v0.2.1

Although GMaps.js does not support requirejs right now, just folk and do some modify to fit my requirement.

Reference the discuession at [here](https://github.com/HPNeo/gmaps/pull/64), and change to requirejs module based on [Felipe Leusin](https://github.com/felipeleusin) [commit](https://github.com/HPNeo/gmaps/commit/585aabf55b7a13d3e551348fadc8d5757e522725)

If you want to use it, just pick a gmaps-amd.js, make sure you have jquery & [async](https://github.com/millermedeiros/requirejs-plugins) in you requrejs settings, then just use `gmaps` module, that's it!
