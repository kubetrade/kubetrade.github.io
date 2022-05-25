# Kubetrade

Kubetrade is a collection of trading applications which demonstrate patterns of deployment and integration. 

# Guiding Principles

* Zero Trust
* Principle of Least Privilege
* Serverless First
* Source control driven processes
  * Fully automated

# Environments

[DEV] - dev
[TEST] - test
[PRODUCTION] - prod

## Domain Suffix
* DEV
  * *.apps.dev001.kubetrade.com
  * ex: https://api.dev.kubetrade.com
* TEST
  * *.apps.test001.kubetrade.com
  * ex: https://api.tst.kubetrade.com
* PROD
  * *.apps.prod001.kubetrade.com
  * ex: https://api.kubetrade.com

# Shared Services

* SSO
  * https://sso.kubetrade.com

# Projects

* shared
  * shared-core
  * shared-market-data
* market-data
  * market-data-api
  * market-data-consumer-cme
  * settlement-data-consumer-cme

# API Organization

* https://api.kubetrade.com/reference-data
* https://api.kubetrade.com/instrument
* https://api.kubetrade.com/counterparty
* https://api.kubetrade.com/market-data
* https://api.kubetrade.com/trade

# Event Topic Organization

* reference-data
* instrument
* counterparty
* market-data
* trade

EVENT_TYPE: CREATE, UPDATE, DELETE
