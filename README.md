![img](./logoteledrive-white.png)

This is the open source project of Google Drive/OneDrive/iCloud/Dropbox alternative using Telegram API for the free unlimited cloud storage.

[![img](https://drive.google.com/uc?id=1o2HnKglEF0-cvtNmQqWZicJnSCSmnoEr)](https://twitter.com/telegram/status/1428703364737507332)

## Motivation

- [Google Photos ends the free storage service](https://www.techradar.com/news/google-photos-price)
- We deserve the free cloud storage service! Pricing: [Google Drive](https://one.google.com/about/plans), [OneDrive](https://one.google.com/about/plans), [Dropbox](https://www.dropbox.com/individual/plans-comparison), [iCloud](https://support.apple.com/en-us/HT201238)


## Getting Started

Read here for full instructions: [teledriveapp.com](https://teledriveapp.com)

## How to Contribute

- Fork and clone this repository
- Commit your changes
- Create a pull request to the `staging` branch

## Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ShankarGanish/tele-drive)

## Folder Structure

We using the monorepo structure with [yarn workspaces](https://classic.yarnpkg.com/en/docs/workspaces/).

```
.
├── README.md
├── package.json
├── server
│   ├── package.json
│   ├── src
│   │   └── index.ts
│   └── tsconfig.json
├── web
│   ├── package.json
│   ├── public
│   ├── src
│   │   ├── pages
│   │   └── App.tsx
│   ├── tsconfig.json
│   └── yarn.lock
└── yarn.lock
```

