# Glasslytics API Docs

## Authorization
Get your secret key in your Account > Plan > View API key.

Add the header:
`Authorization` with value `Bearer <secret>` where `<secret>` is your secret key.

Example:
`Authorization: Bearer sk_83jf764jr92k0xkj4`

## Resources
API Base URL: `https://glasslytics.com/`
### Views
- Path: `/api/v1/views`
- Method: `POST`
- Data: 
  - URL (full path) * **required**
  - useragent
  - referer
  - lang
  - ip

### Actions
- Path: `/api/v1/actions`
- Method: `POST`
- Data: 
  - label * **required**
  - data 
