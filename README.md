# NHS Digital

NHS England Digital is the national provider of digital health technology for the NHS in England. It delivers a comprehensive suite of REST and FHIR APIs covering patient demographics, electronic prescriptions, summary care records, national record location, referrals, GP Connect services, vaccination records, NHS App communications, and clinical data services.

## Developer Portal

https://digital.nhs.uk/developer

## API Catalogue

https://digital.nhs.uk/developer/api-catalogue

The catalogue contains over 90 APIs and integrations across standards including FHIR R4, HL7 V3, REST, SOAP, and MESH messaging.

## API Platform

APIs are hosted on the NHS API platform at `api.service.nhs.uk` with:

- Sandbox: `https://sandbox.api.service.nhs.uk`
- Production: `https://api.service.nhs.uk`

## Key APIs

| API | Description |
|-----|-------------|
| Personal Demographics Service (FHIR) | National NHS patient demographic database |
| Electronic Prescription Service (FHIR) | National electronic prescription transmission |
| Summary Care Record (FHIR) | National electronic clinical summary records |
| National Record Locator (FHIR) | Locate patient records across NHS organisations |
| Booking and Referral (FHIR) | NHS BaRS standard for bookings and referrals |
| GP Connect Appointment Management | GP appointment booking and management |
| e-Referral Service (FHIR) | National paperless referral system |
| NHS App API | Patient-facing NHS App messaging |
| NHS Login API | Patient authentication via OpenID Connect |
| Directory of Healthcare Services | NHS service search across England |
| MESH API | NHS national messaging infrastructure |
| Health Research Data Catalogue | NHS dataset metadata for researchers |

## Authentication

Four authentication patterns are supported:

1. **API Key** — application-restricted, lower-sensitivity APIs
2. **OAuth 2.0 Private Key JWT** — application-restricted, sensitive data APIs
3. **NHS CIS2 Care Identity** — user-restricted, healthcare workers
4. **NHS Login** — user-restricted, patients and the public

Documentation: https://digital.nhs.uk/developer/guides-and-documentation/security-and-authorisation

## Access and Pricing

All NHS Digital APIs are free to access. Access requires:

1. An Organisation Data Service (ODS) code
2. Completion of the NHS Data Security and Protection Toolkit
3. Digital Onboarding Service application and NHS England approval
4. Signing a connection or data sharing agreement (for production)

Onboarding: https://digital.nhs.uk/developer/guides-and-documentation/onboarding-process

## Support

- Developer support: https://digital.nhs.uk/developer/help-and-support
- Developer community: https://developer.community.nhs.uk
- Email: api.management@nhs.net

## GitHub

https://github.com/NHSDigital
