# queryLegacyRewards

Returns data about the rewards available in SC2.

```js
const StarCraft2API = require('starcraft2-api');

const sc2api = new StarCraft2API({
  region: 'us',
  clientId: 'client id',
  clientSecret: 'client secret'
});

const data = await sc2api.queryLegacyRewards(1);

console.log(data);

// Do something with data

```

## Parameters

* **regionId** (string / number) - region id