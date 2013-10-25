openseadragon-netbeans
======================

This is just the netbeans configuration I use for my development on [OpenSeadragon](https://github.com/openseadragon/openseadragon).
It allows to easily run the debugger and the formatting has been set to follow as closely as possible the OpenSeadragon's formatting scheme.

To use it, clone this repository and then clone both your [OpenSeadragon](https://github.com/openseadragon/openseadragon) and [example-images](https://github.com/openseadragon/example-images) forks inside the public_html folder.
Make sure to checkout the gh-pages branch of example-images.

```
$ git clone https://github.com/avandecreme/openseadragon-netbeans.git
$ cd openseadragon-netbeans/public_html
$ git clone https://github.com/YOUR_USER_NAME/openseadragon.git
$ git clone https://github.com/YOUR_USER_NAME/example-images.git
$ cd example-images
$ git checkout origin/gh-pages -b gh-pages
```

You should now be able to open the project in netbeans. You can modify the index.html file to your needs.
Tested with netbeans 7.4.


Note: there is no integration with grunt. This project only allows to easily debug and format with netbeans. You still will have to build, test and package from the command line.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/avandecreme/openseadragon-netbeans/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

