# Vercel GeoIP

Returns Vercel's Geolocation headers back on requests for a simple GeoIP service without tracking.

Exposes:

- `country` — [`x-vercel-ip-country`](https://vercel.com/docs/concepts/edge-network/headers#x-vercel-ip-country)
- `countryRegion` — [`x-vercel-ip-country-region`](https://vercel.com/docs/concepts/edge-network/headers#x-vercel-ip-country-region)
- `city` — [`x-vercel-ip-city`](https://vercel.com/docs/concepts/edge-network/headers#x-vercel-ip-city)
- `latitude` — [`x-vercel-ip-latitude`](https://vercel.com/docs/concepts/edge-network/headers#x-vercel-ip-latitude)
- `longitude` — [`x-vercel-ip-longitude`](https://vercel.com/docs/concepts/edge-network/headers#x-vercel-ip-longitude)
- `ip` — [`x-forwarded-for`](https://vercel.com/docs/concepts/edge-network/headers#x-forwarded-for)
- `region` — [`x-vercel-id-req`](https://vercel.com/docs/concepts/edge-network/headers#x-vercel-id-req)
