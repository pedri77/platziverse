#platiziverse-db

## Usage

```js

const setupDatabase = require (platziverse-db)

setupDatabase(config).then(db =>{
    const { Agent, Metric } = db
    // const Agent = db.Agent
    // cont Metric = db.Metric
}).catch(err => console.error(err))
```
