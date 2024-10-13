
Fork of Saiku in process!!!

## Setup

### Build Instructions

```sh
mvn clean install -DskipTests

mvn clean clover2:setup test clover2:aggregate clover2:clover
```

### Update project version

To update the pom versions run:

```sh
mvn versions:set -DnewVersion=3.x.x
```

Then remove the backups with:

```sh
find . -name "*.versionsBackup" -type f -delete
```

## Get Saiku License

Saiku is open source and free to use. Our default server does ship with a license server installed. To get a license you can visit https://licensing.meteorite.bi and get a FREE license which is pinned to the major release of the server. This helps us with a more accurate picture of installation numbers and deployments.

## Wiki

* [Saiku Wiki](https://saiku-documentation.readthedocs.io/en/latest/)

## Community

* [Saiku Community](https://community.meteorite.bi/)

## Bugs and Feature Requests

* [GitHub Issues](https://github.com/OSBI/saiku/issues/new)

## Discussion List

* [Saiku Dev Group](https://groups.google.com/a/saiku.meteorite.bi/forum/#!forum/dev)
* [Saiku User Group](https://groups.google.com/a/saiku.meteorite.bi/forum/#!forum/user)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/saiku)
* [Freenode IRC - Channel: ##saiku](https://webchat.freenode.net/?randomnick=1&channels=%23%23saiku)

## Browser Support

We do care about it.

| ![Edge](https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) |
| --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Latest ✔                                                                                      | Latest ✔                                                                                 | Latest ✔                                                                                    | Latest ✔                                                                              | Latest ✔                                                                                 |

## Team

[Saiku](https://www.meteorite.bi) is maintained by these people and a bunch of awesome [contributors](https://github.com/OSBI/saiku/graphs/contributors).

| [![Breno Polanski](https://avatars7.githubusercontent.com/u/1894191?v=4&s=70)](https://github.com/brenopolanski) | [![Bruno Catão](https://avatars4.githubusercontent.com/u/785116?v=4&s=70)](https://github.com/brunogamacatao) | [![Mark Cahill](https://avatars5.githubusercontent.com/u/200365?v=4&s=70)](https://github.com/thinkjson) | [![Paul Stoellberger](https://avatars5.githubusercontent.com/u/454645?v=4&s=70)](https://github.com/pstoellberger) | [![Tom Barber](https://avatars6.githubusercontent.com/u/103544?v=4&s=70)](https://github.com/buggtb) |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| [Breno Polanski](https://github.com/brenopolanski)                                                               | [Bruno Catão](https://github.com/brunogamacatao)                                                              | [Mark Cahill](https://github.com/thinkjson)                                                              | [Paul Stoellberger](https://github.com/pstoellberger)                                                              | [Tom Barber](https://github.com/buggtb)                                                              |

## Contributing

Check [CONTRIBUTING.md](./CONTRIBUTING.md) for more details. Some important information:

* To get started, [sign the Contributor License Agreement](https://www.clahub.com/agreements/OSBI/saiku).

* If you find a bug then please create an issue [here](https://github.com/OSBI/saiku/issues/new).

* If you have a feature request, then please get in touch. We'd love to hear from you! Send a email for: [info@meteorite.bi](mailto:info@meteorite.bi)

## History

For detailed changelog, check [Releases](https://github.com/OSBI/saiku/releases).

## License

Saiku and the Saiku UI are free software. The UI, contained in this repository, is available under the terms of the Apache License Version 2. A copy is attached for your convenience.

**[⬆ back to top](#readme)**
