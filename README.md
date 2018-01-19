# country-iso-3-to-2

> Convert a country code ISO 3166-1 Alpha-3 to ISO 3166-1 Alpha-2

## Install

```sh
$ npm install country-iso-3-to-2
```

## Usage

```js
const getCountryISO2 = require("country-iso-3-to-2");

getCountryISO2("BRA")
// "BR"

getCountryISO2("USA")
// "US"
``` 

## API

### getCountryISO2(countryCode)

**Parameter**:
A string with a country code in ISO 3166-1 Alpha-3

**Return**:
A string with the country code in ISO 3166-1 Alpha-2

---

## License

MIT © [VTEX](https://www.vtex.com)
