# realm-guard

A Telegram group management bot made with Node and Telegraf.

Currently at a WIP stage and is not fit for production use.

## Features

- [x] Generic bot commands
- [x] Banning user
- [x] Unbanning user
- [ ] Kicking user
- [ ] Muting user
- [ ] Unmuting user
- [ ] Warning user
- [ ] Clearing user warns
- [ ] Reducing user warns by 1
- [ ] Purging the group chat to replied message
- [ ] Showing user warns
- [ ] Setting welcome message
- [ ] Setting farewell message
- [ ] Reporting user

> Features are subject to change and will probably change depending on the needs

## Running

1. Install the dependencies using `pnpm install` or `npm install` or whichever node package manager you prefer.
2. Copy the example `.env.example` environment table file and rename it to `.env`.
3. Copy your bot token into the environment variable `BOT_TOKEN` as its value.
4. Run `npm run dev` or `pnpm run dev` or `yarn run dev` or whichever node package manager you prefer as long as it runs.
5. Voila!

## License

MIT