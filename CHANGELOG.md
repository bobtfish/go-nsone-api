## 2.6.1 (July 12, 2021)
FEATURES:
* Adds missing `records_allow` and `records_deny` fields to account permissions

## 2.6.0 (July 6, 2021)
FEATURES:
* Adds support for subdivision metadata

## 2.5.1 (May 20, 2021)
BUG FIXES:
* Handle rate limit despite HTTP error returned from API [#127](https://github.com/ns1/ns1-go/pull/127)

## 2.5.0 (April 5, 2021)
FEATURES:
* Adds support for `tags_allow` and `tags_deny` fields in IPAM and DHCP DDI permissions.

## 2.4.5 (March 31, 2021)
FEATURES:
* Adds support for DS record type

## 2.4.4
FEATURES:
* Added missing `manage_ip_whitelist` permission to the account permissions section

## 2.4.3
FEATURES:
* Added support for tagging in DDI on records and zones

## 2.4.2
FEATURES:
* Added support for "cost" meta option on records

## 2.4.1
BUGFIX:
* Fix incorrect tag

## 2.4.0
FEATURES:
* Exported mock API service - @iamgnat

## 2.3.0 (March 19, 2020)
FEATURES:
* Support for pulsar metadata on answers

## 2.2.1 (Febuary 14, 2020)
BUG FIXES
- Resolves a panic and several type issues with the ASN field.

## 2.2.0 (January 15, 2020)
FEATURES:
* Added support for various fields on team, user, and API key resources.

## 2.1.0 (January 9, 2020)
FEATURES:
* Added support for DDI permissions

## 2.0.0 (January 9, 2020)

* Begin semantic versioning
