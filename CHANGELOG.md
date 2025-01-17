# Changelog

All notable changes to `vrajroham/laravel-bitpay` will be documented in this file

---
#### v5.0.0 - 2021-12-09

* v5 Upgrade by @alexstewartja in https://github.com/vrajroham/laravel-bitpay/pull/38:
  + Updated BitPay client dependency to v6.0.2111
  + Implemented exchange rates (single/pair)
  + Deprecated constants that already exist in core library
      - Also added return codes that can be used to verify webhooks for the following resources:
          + Invoices
          + Recipients
          + Payouts
  + Implemented `Settlements` resource
  + Implemented `Ledgers` resource
  + Implemented `Recipients` resource
  + Implemented `Payouts`/`PayoutBatches` resources
  + Added support for `payout` facade
  + Updated UX of API Token generation command
  + Optimized webhook URL (notificationURL) auto-population
  + Added v4 -> v5 to migration guide

#### v2.0.2

- Fixed **livenet** token `URL` [#14](https://github.com/vrajroham/laravel-bitpay/pull/14) by [@IvanG11](https://github.com/IvanG11)
