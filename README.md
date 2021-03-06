# Mansave
[![Java CI with Maven](https://github.com/MadeByIToncek/Mansave/actions/workflows/maven.yml/badge.svg)](https://github.com/MadeByIToncek/Mansave/actions/workflows/maven.yml)[![CodeQL](https://github.com/MadeByIToncek/Mansave/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/MadeByIToncek/Mansave/actions/workflows/codeql-analysis.yml)

Tento plugin byl inspirován youtuberem [McBirken](https://www.youtube.com/channel/UCQaNjJ7Iwx-l91F5_gBJhiQ)
TODO: Fill out this long description.

## Obsah

- [Bezbečnost](#Bezbečnost)
- [Instalace](#Instalace)
- [Použití](#Použití)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Bezbečnost

## Instalace

1. Stáhni si z [Releases](https://github.com/MadeByIToncek/Mansave/releases) nejnovější verzi ("Mansave-x.x.jar").
3. Stáhni si [Paper](https://papermc.io/api/v2/projects/paper/versions/1.16.5/builds/443/downloads/paper-1.16.5-443.jar) a jednou ho spusť.
4. Přesuň Mansave-*.*.jar do složky "plugins"
5. Zapni server

## Použití

* `/mansave start` - Spustí hru
* `/mansave stop` - Ukončí hru
* `/mansave addHunter <hráč>` - Přidá hráče do seznamu lovců
* `/mansave removeHunter <hráč>` - odebere hráče ze seznamu lovců
* `/mansave huntersTakeDamage <true|false>` - false = lovci si nemůžou ubrat damage
* `/mansave huntersHungerLoss <true|false>` - false = lovci neztrácí hlad.
* `/mansave suicidalHungerLoss <true|false>` - false = speedrunnerovi neubývá hunger
* `/mansave countdownInSeconds <sekundy>` - časový limit (normálně 300s = 5min)

## Reset seedu

```
Pro reset seedu zastavte server a smažte původní svět (odstraňte složky "world", "world_nether" a "world_the_end").
```

## Maintainers

[@MadeByIToncek](https://github.com/MadeByIToncek)

## Contributing

PRs accepted.

// Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## Licence

MIT © 2021 IToncek
