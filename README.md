# confs.info

## Running

- `elm package install`
- `elm make src/Main.elm --output elm.js`
- `open index.html`

## Tests

- `cd test`
- `elm package install`
- `npm install -g`
- `elm make AllTests.elm --output test.js`
- `node test.js`

or

- `npm run test` to watch and run on save

## Rationale

I wanted to make a central place for designers and developers to find
conferences they might be interested in. Conferences in any language, location,
or focus are welcome so long as they:

- Are targeted at designers and/or developers
- Have a set location and date
- Are the type of conference one might travel to (no local meetups, etc.)

If you know of a conference this list is missing (or want to add a feature), open a pull request!
