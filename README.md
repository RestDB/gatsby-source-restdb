# gatsby-source-restdb

This is a source plugin to fetch data from a restdb.io database. 

## Set The Config

In `gatsby-config.js`:

```js
module.exports = {
    plugins: [
        {
            resolve: 'gatsby-source-restdb',
            options: {
                apikey: "custom or full access api key"
            },
        },
    ],
}
```
