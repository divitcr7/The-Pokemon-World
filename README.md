# Project Photos
| | |
|:-------------------------:|:-------------------------:|
| <img width="1733" alt="image" src="https://github.com/divitcr7/Theo-Pokemon-World/assets/67183559/8eb8ef38-68ad-4cfa-bbc2-d5225c7312db"> | <img width="1722" alt="image" src="https://github.com/divitcr7/Theo-Pokemon-World/assets/67183559/1ebf6cd2-11b9-49ad-b83b-2b0a77a17d53">|
| | |
|<img width="1713" alt="image" src="https://github.com/divitcr7/Theo-Pokemon-World/assets/67183559/fffbde37-af02-410d-8170-1ba75eae389d"> |<img width="1729" alt="image" src="https://github.com/divitcr7/Theo-Pokemon-World/assets/67183559/0fe80153-159a-40c8-bd90-3d164a578e4b">
|
## Pokemon Data

All Pokemon data used in this project comes from [PokeAPI GraphQL Beta](https://pokeapi.co/docs/graphql).  
Playground: https://beta.pokeapi.co/graphql/console/

All Pokemon images (artwork) comes from https://github.com/PokeAPI/sprites.

## Getting Started

1. Install dependencies using `yarn install`.
2. Prepare environment variables (`.env.local`), refer to [`.env.example`](./.env.example) file.
3. Prepare data using `yarn prepare-data`.
4. Run development server using `yarn dev`.

For production, use this script: `yarn build && yarn start`

## Quality Check

- Prettier check: `yarn format`
- ESLint check: `yarn lint`
- TypeScript check: `yarn lint:types`
- End-to-end test check: `yarn test:e2e`

## Misc.

This project is using [Next.js [TypeScript] + Tailwind CSS Starter Template](https://github.com/afiiif/nextjs-ts-starter-template).  
The starter template contains:

- ⚡️ [Next.js 12](https://nextjs.org/)
- ⚛️ [React 18](https://reactjs.org/)
- 🎐 [Tailwind CSS 3](https://tailwindcss.com/)
- 🪄 [Prettier](https://prettier.io/) — Format your code automatically, this will also run **on save**
- 🧼 [ESLint](https://eslint.org/) — Find & fix problems in your code, and **auto sort** your imports
- 🐶 [Husky](https://www.npmjs.com/package/husky) & [Lint Staged](https://www.npmjs.com/package/lint-staged) — Check & fix code when commit, block commit if bad code detected
- 📜 [Commit Lint](https://github.com/conventional-changelog/commitlint) — Make sure the commit message follows the conventional commit
- ⚙️ [Github Actions](https://github.com/features/actions) — Check your code on push & pull-request
- 🤖 [Dependabot](https://github.com/dependabot) — Create pull-request to update your dependencies
- 🔗 [Absolute Import](./tsconfig.json) — Import modules using `@/` prefix
- 💟 [React Icons](https://react-icons.github.io/react-icons/) — Include popular icons in your React projects easily
- 🌟 [React Power-Ups](https://github.com/afiiif/react-power-ups) — Collection of React hooks to speed-up your app development
