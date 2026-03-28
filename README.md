# License Plate Owner Lookup API

DPPA-compliant license plate to owner lookup API — built and fulfilled by a licensed California Private Investigator (CA PI License #27617).

## What It Does
Send a license plate number and state, get back verified owner data. Results returned within 1–2 business days through a secure order tracking URL.

## Coverage
36 US states — DPPA-compliant only

## DPPA Permissible Purposes
- Purpose 1 — Government agency
- Purpose 2 — Motor vehicle safety
- Purpose 8 — Insurance
- Purpose 9 — Licensed private investigator

## API Endpoint
```
GET https://license-plate-owner.com/api-endpoint/lookup.php?plate=ABC1234&state=CA&purpose=9
```

## Parameters
| Parameter | Required | Description |
|-----------|----------|-------------|
| plate | Yes | License plate number |
| state | Yes | Two-letter state code |
| purpose | Yes | DPPA purpose code (1, 2, 8, or 9) |

## Sample Response
```json
{
  "status": "success",
  "order_url": "https://license-plate-owner.com/order/track/?id=XXXXXXXX"
}
```

## Quick Start
- 📄 [Full API Documentation](https://license-plate-owner.com/api/)
- ⚡ [Free Tier on RapidAPI](https://rapidapi.com/ljkc916/api/license-plate-owner-lookup)
- 🧪 [Postman Collection](https://www.postman.com/licenseplatelookup-3057154)

## Code Examples

**cURL**
```bash
curl "https://license-plate-owner.com/api-endpoint/lookup.php?plate=ABC1234&state=CA&purpose=9"
```

**Python**
```python
import requests

params = {"plate": "ABC1234", "state": "CA", "purpose": "9"}
response = requests.get("https://license-plate-owner.com/api-endpoint/lookup.php", params=params)
print(response.json())
```

**PHP**
```php
$url = "https://license-plate-owner.com/api-endpoint/lookup.php?plate=ABC1234&state=CA&purpose=9";
$response = file_get_contents($url);
$data = json_decode($response, true);
```

**JavaScript**
```javascript
const res = await fetch("https://license-plate-owner.com/api-endpoint/lookup.php?plate=ABC1234&state=CA&purpose=9");
const data = await res.json();
console.log(data);
```

## About
Built by [Lance Casey & Associates](https://license-plate-owner.com/) — Sacramento, CA
Licensed California Private Investigator — CA PI #27617
