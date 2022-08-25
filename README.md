### escookie issue reproduction

es-cookie has gone ESM only as a minor version, which breaks any consumers of @auth0/auth0-spa-js who are using CJS.

#### To reproduce

`yarn test`
