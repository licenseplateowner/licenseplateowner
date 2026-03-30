# License Plate Lookup API (DPPA Compliant Vehicle Owner Data API)

A developer-friendly API to perform license plate lookups and retrieve vehicle-related data for lawful and permissible use cases.

This API is built and maintained by a licensed private investigator and is designed for developers, investigators, attorneys, and businesses that require access to vehicle information in a compliant and structured format.

---

## 🚀 Live API Access

- RapidAPI: https://rapidapi.com/ljkc916/api/license-plate-owner-lookup  
- Postman Collection: https://www.postman.com/licenseplatelookup-3057154  
- Website: https://license-plate-owner.com/api/

---

## 🔍 What This API Does

This API allows you to:

- Lookup vehicle information by license plate  
- Retrieve vehicle make, model, and year  
- Access available registration-related data (where permitted)  
- Support investigative and legal research workflows  
- Integrate vehicle lookup functionality into apps and systems  

---

## ⚖️ DPPA Compliance (Important)

This API is designed to align with the Driver’s Privacy Protection Act (DPPA).

Access to registered owner information is restricted and only available when a valid permissible purpose exists, such as:

- Legal investigations  
- Litigation and court-related matters  
- Fraud or identity investigations  
- Business verification  
- Insurance or claims investigations  

Users are responsible for ensuring compliance with all applicable laws before using this API.

---

## 🧠 Common Use Cases

- Private investigators locating vehicle-related information  
- Attorneys preparing cases or subpoenas  
- Process servers verifying vehicle ownership details  
- Developers building vehicle lookup tools  
- OSINT researchers gathering vehicle intelligence  

---

## 💻 Example Request

### cURL

```bash
curl --request GET \
  --url "https://license-plate-owner.p.rapidapi.com/lookup?plate=ABC1234&state=CA" \
  --header "X-RapidAPI-Key: YOUR_API_KEY" \
  --header "X-RapidAPI-Host: license-plate-owner.p.rapidapi.com"
