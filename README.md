# mensa
Parser for openmensa.org. The parser runs in a [Github action](https://github.com/cvzi/mensa/actions?query=workflow%3ARunParsers) and pushes the XML feeds to [Github pages](https://cvzi.github.io/mensa/)

|  Feeds       |                                         Status                                                                                                                  |                     Cron                                                                                                                                      |
|:------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| today        | [![RunParsersToday](https://github.com/cvzi/mensa/workflows/RunParsersToday/badge.svg)](https://github.com/cvzi/mensa/actions?query=workflow%3ARunParsersToday) | [32 6-11 * * 1-5](https://crontab.guru/#32_6-11_*_*_1-5 "“At minute 32 past every hour from 6 through 11 on every day-of-week from Monday through Friday.” ") |
| all          | [![RunParsers](https://github.com/cvzi/mensa/workflows/RunParsers/badge.svg)](https://github.com/cvzi/mensa/actions?query=workflow%3ARunParsers)                | [12 6 * * *](https://crontab.guru/#12_6_*_*_* "“At 06:12.” ")                                                                                                 |
