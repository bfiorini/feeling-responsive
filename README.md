# Les Cabris Explorateurs

## This my website and blog

## Installation

**Step 1.** Install [Bundler](http://bundler.io/) and then run `bundle install`.

**Step 2.** Install [NodeJS and NPM](https://github.com/nodesource/distributions#deb).
```shell
curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash -
sudo apt-get install -y nodejs
```

**Step 3.** Install [Yarn](https://yarnpkg.com/en/docs/install).
```shell
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt-get update && sudo apt-get install yarn
```

**Step 4.** Install dependencies
```shell
yarn
```

## Usage

See `package.json` NPM scripts.

### `yarn build`
### `yarn start`
### `yarn clean`
### `yarn update`
...
