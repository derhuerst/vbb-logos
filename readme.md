# vbb-logos

**Nice SVG logos for Berlin & Brandenburg public transport.**

![CC-licensed](https://img.shields.io/github/license/derhuerst/vbb-logos.svg)


## Usage

The logos are defined in [`signets.svg`](signets.svg). Put `signets.svg` in your web project and embed logos as follows.

```css
.icon { width: 1em; height: 1em; }
```

```html
<svg class="icon subway" viewBox="0 0 100 100">
	<use xlink:href="path/to/signets.svg#subway"/>
</svg>
```

*Note*: IE does not support SVG `<use>` with things from other files.

*Pro Tip*: If you want to hotlink `signets.svg`, use `https://cdn.rawgit.com/derhuerst/vbb-logos/master/signets.svg`.



## Attribution

The logos for *Regionalverkehr*, *S-Bahn*, *U-Bahn*, *Tram*, *Ruf-Bus*, *Express-Bus* and *Ausflugs-Bus* are © VBB. [more infos](http://www.vbb.de/de/article/ueber-uns/media-service/produktsignets/3306.html)

- [The logo for *Bus* is from Wikimedia Commons.](https://commons.wikimedia.org/wiki/File:BUS-Logo-BVG.svg)
- [The logo for *X-Bus* is from Wikimedia Commons.](https://commons.wikimedia.org/wiki/File:X-Bus_VBB.svg)
- [The logo for *MetroBus* is from Wikimedia Commons.](https://commons.wikimedia.org/wiki/File:MetroBus.svg)
- [The logo for *Fähre* is from Wikimedia Commons.](https://commons.wikimedia.org/wiki/File:F%C3%A4hre-Logo-BVG.svg)
- [The logo for *MetroTram* is from Wikimedia Commons.](https://commons.wikimedia.org/wiki/File:MetroTram.svg)

## Contributing

If you **have a question**, **found a bug** or want to **propose a feature**, have a look at [the issues page](https://github.com/derhuerst/vbb-logos/issues).
