[![accord project](https://img.shields.io/badge/powered%20by-accord%20project-19C6C8.svg)](https://www.accordproject.org/)

# Accord Internship Contract
 This is a sample accord template for internship contracts.

## Setup
- Clone this repository
- cd into the directory

```shell
cd accord-internship-contract/
```

- run the following command
```shell
npm install
```

## Usage
- There is sample contract data present in sample.md.
- Run the following command and the output will be a JSON object containing age value.
```shell
npx cicero trigger
```

- To extract the data from contract text.
```shell
npx cicero parse --output data.json
```

- To update the contract text data there are two ways
  - Change the data directly in text/sample.md OR
  - Update data.json then draft the contract text using
  ```shell
  npx cicero draft --output text/sample.md
  ```
## Documentation

- The report on this project is generated using AsciiDoctor
- Install [AsciiDoctor](https://asciidoctor.org/docs/user-manual/#installing-the-asciidoctor-ruby-gem)
- For Debian and Ubuntu
```sh
sudo apt-get install asciidoctor
```
- Install AsciiDoctor Diagram
```sh
gem install asciidoctor-diagram
```
- Generate html document
```sh
asciidoctor -a mmdc=node_modules/.bin/mmdc -r asciidoctor-diagram Report.adoc
```
- This will generate a Report.html file which can be opened using a browser.