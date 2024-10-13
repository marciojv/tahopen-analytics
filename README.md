
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


## Browser Support

We do care about it.

| ![Edge](https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) |
| --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Latest ✔                                                                                      | Latest ✔                                                                                 | Latest ✔                                                                                    | Latest ✔                                                                              | Latest ✔                                                                                 |

## Team of Saiku (this is a original team before fork)

[Saiku](https://www.meteorite.bi) is maintained by these people and a bunch of awesome [contributors](https://github.com/OSBI/saiku/graphs/contributors).

| [![Breno Polanski](https://avatars7.githubusercontent.com/u/1894191?v=4&s=70)](https://github.com/brenopolanski) | [![Bruno Catão](https://avatars4.githubusercontent.com/u/785116?v=4&s=70)](https://github.com/brunogamacatao) | [![Mark Cahill](https://avatars5.githubusercontent.com/u/200365?v=4&s=70)](https://github.com/thinkjson) | [![Paul Stoellberger](https://avatars5.githubusercontent.com/u/454645?v=4&s=70)](https://github.com/pstoellberger) | [![Tom Barber](https://avatars6.githubusercontent.com/u/103544?v=4&s=70)](https://github.com/buggtb) |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| [Breno Polanski](https://github.com/brenopolanski)                                                               | [Bruno Catão](https://github.com/brunogamacatao)                                                              | [Mark Cahill](https://github.com/thinkjson)                                                              | [Paul Stoellberger](https://github.com/pstoellberger)                                                              | [Tom Barber](https://github.com/buggtb)                                                              |

## Contributing

Check [CONTRIBUTING.md](./CONTRIBUTING.md) for more details. Some important information:


## History

For detailed changelog, check [Releases](https://github.com/OSBI/saiku/releases).

## License

Saiku and the Saiku UI are free software. The UI, contained in this repository, is available under the terms of the Apache License Version 2. A copy is attached for your convenience.

**[⬆ back to top](#readme)**
