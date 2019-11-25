# js: my javascript collections

<!-- vim: ft=markdown nospell
-->
a bunch of personal javascripts usable via CDN ([jsdelivr][jd], [cloudflare][cf] or [github][gh])
(last [commit](https://github.com/iglake/js/commit/) & [releases](https://github.com/iglake/js/releases))

 * [inc.js][1] : a javascript that replace div with class=include with the content of its data-src's attribute
 * [inc-fp.js][2] : a javascript to include and render a markdown file from framapad
 * [...](https://cdn.jsdelivr.net/gh/iglake/js@master/dist/)

[1]: https://cdn.jsdelivr.net/gh/iglake/js@master/dist/inc.js
[2]: https://cdn.jsdelivr.net/gh/iglake/js@master/dist/inc-fp.js



 * other URLs for accessing the files :
    - <https://gateway.ipfs.io/ipfs/QmdY5iPf1sEfgSeyYEvERJp63XJsDag8is335byUkuGgb6/www/js>
    - <https://cloudflare-ipfs.com/ipfs/Qmdq5LNvDmVeRQMJEXg4AW8n2jeTfEY1zuqaJPBYJEdwfX/js>
    - <https://iglake.github.io/js>

[![version](https://badge.fury.io/gh/iglake%2Fjs.svg)](https://badge.fury.io/gh/iglake%2Fjs)
[![](https://data.jsdelivr.com/v1/package/gh/iglake/js/badge)](https://www.jsdelivr.com/package/gh/iglake/js)

### Examples:

 * collaborative framapad "web-page" : <http://ipfs.io/ipfs/Qmdq5LNvDmVeRQMJEXg4AW8n2jeTfEY1zuqaJPBYJEdwfX/js/examples/frama.htm>
 *  or <https://iglake.github.io/js/examples/frama.htm>

 *  ipfs node detection : <https://iglake.github.io/js/examples/ipfsdetect.htm>

 * misc : about [how](https://www.one-tab.com/page/XuCCeOg2SkSSwTD8JzvWfw) to publish on GitHub (see <https://ipfs.io/ipfs/QmX87y253JbdLWUcd5Qdd3HaBYpoiqr8wVUYQHiuNYHAG2/>)

 * blockRing™ hash : qm=[zdj7WY9XupL113pQbSWLFS5NaDmKktBNeYiQeLh1GoyYe32VL](http://gateway.ipfs.io/ipfs/zdj7WY9XupL113pQbSWLFS5NaDmKktBNeYiQeLh1GoyYe32VL)

### Usage:

```html
<!-- previous revision: 9309d01
<script src="https://cdn.statically.io/gh/iglake/js/9309d01/dist/inc-fp.js">
-->
<!-- current revision: latest : https://github.com/iglake/js/commit/master -->
<script src="https://cdn.jsdelivr.net/gh/iglake/js@master/dist/inc-fp.min.js">
</script>
 ```

[gh]: http://github.com/iglake/
[jd]: https://www.jsdelivr.com/package/gh/iglake/js
[cf]: https://cloudflare-ipfs.com/ipfs/Qmdq5LNvDmVeRQMJEXg4AW8n2jeTfEY1zuqaJPBYJEdwfX/js

clone it with the following command :
  ```git clone https://github.com/iglake/js.git```

### Currently working on

[ipfs-mutables.js](http://127.0.0.1:8080/ipfs/QmWxb7Zx27rg8usPFiZR9PmMsisaZrL8HNENCtkiaiLP27/ipfs-mutables.js)


### Last fix ...

 - bug in ipfs-mutables !
 - added %email% to sub.js
