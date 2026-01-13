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
### 2025-09-01
* Declare all extensions that this extension modifies
* Do not repeat properties of other extensions
* Move `AboveThreshold` type into each referring field
### 2025-04-30
* Add \"wholeListMerge\" to some properties
* Various small fixes
### 2025-02-22
* Initial version
