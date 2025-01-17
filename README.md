# Karlsen Transaction Report

Generates a CSV file for all your Karlsen transactions.


## Want to just get to generating your report?

You can use the deployment at (https://karlsen-transaction-report-web.vercel.app/)

## Requirement

- NodeJS (v16+)

## Usage

1. Download this repository and unzip (or clone it if you know how)
2. Open a terminal/cmd and go to the directory you downloaded this at, then run `npm install`. This will install dependencies.
3. Create a file `addresses.txt` in this directory. In this file, you will list all your address - one per line
```
karlsen:myaddress
karlsen:myotheraddress
karlsen:anotherone
```
4. To generate your transaction report run `npm run generate`

This will generate the file `karlsen-transactions.csv`. This CSV is currently compatible with Koinly only.

## Notes
- Compound transactions and transactions sending to yourself are ignored
- Assumes addresses from exchanges are treated as not your own
- If you notice the report is inaccurate, first make sure you actually listed all addresses you care about in `addresses.txt`

## Found this useful?

Consider donating to `karlsen:qqhfdkxptlmwldafc9fggzss4vzvd6y0z5xtn404ydz0t0qqnlp5zm5xhlzdd`
