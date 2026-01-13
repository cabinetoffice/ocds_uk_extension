# OCDS for the United Kingdom
This public OCDS extension adds fields and codes that are specific to the United Kingdom.
## Guidance
To be added.
## Legal context
To be added.
## Example
To be added.
## Changelog
### 2026-01-13
* Add `contracts/terminationRationaleClassifications` array (singular `contracts/terminationRationaleClassification` still valid but deprecated)
* Add `contracts/implementation/metrics/observations/measureClassification`
* Add fields to `contracts/implementation/performanceFailures`:
  * `requirement`
  * `description`
  * `decisionDate`
  * `penaltyDate`
  * `penaltyType`
  * `penaltyTypeEntered`
  * `penaltyValue`
  * `partialTermination`
  * `suppliers`
  * `documents`
* Add \"implementationNotice\" as a `documentType` (used for UK9 contract performance notice)
### 2025-02-22
* Initial version
