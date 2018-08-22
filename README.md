# Static Website with Pingy CLI

## Install Pingy
  ```
  npm install @pingy/cli --global
  ```

## Setup

  ```
  git clone git@github.com:huychau/pingy.git
  cd pingy/
  npm install
  ```

## Run
  ```
  pingy dev // Development
  pingy export // Build
  ```

## Custom `pingy export`
  `pingy export` include some files, folders unnecessary by default, so we need config to *exclude* or *remove* it.

  - Exclude `views/`, `*.md`, `*.json` [here](pingy.json#L13)
  - Remove unnecessary files, folders [here](package.json#L9)
  - Run the export `npm run export`
## References
  - [Pingy CLI website](https://pin.gy/cli/)
  - [Pingy CLI Github](https://github.com/pingyhq/pingy-cli)
