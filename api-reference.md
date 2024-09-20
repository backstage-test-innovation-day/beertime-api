# API Reference

## GET /

### Description
This endpoint returns a GIF file to confirm that it is beer time.

### Request
- **Method**: GET
- **URL**: `/`

### Response
- **Content-Type**: `image/gif`
- **Body**: The GIF file.

### Example Request
```bash
curl -X GET "https://[your-api-url.com](https://isbeertime.apps.sandbox-m3.1530.p1.openshiftapps.com/)/"
