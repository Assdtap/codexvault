# codexvault
// accessories/examples/onboarding-assistant.manifest.json
{
  "id": "onboarding-assistant",
  "name": "New Steward Onboarding Assistant",
  "version": "1.0.0",
  "owner": "SIN Foundation",
  "publicKeys": ["ABCD1234..."],
  "quadSeal": {
    "spiritualOathRef": "oath/v1",
    "legalRef": "covenant/2025-01",
    "procedureRef": "SOP/onboarding/v1",
    "signingKeyFingerprint": "F1:23:45:..."
  },
  "events": [
    { "topic": "induction.completed", "schema": "sin.induction.v1", "signatureAlg": "PGP" }
  ]
}