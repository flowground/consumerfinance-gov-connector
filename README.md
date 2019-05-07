# ![LOGO](logo.png) The Consumer Financial Protection Bureau **flow**ground Connector

## Description

A generated **flow**ground connector for the The Consumer Financial Protection Bureau API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/consumerfinance.gov/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:07+03:00

## API Description

Learn more about home mortgage data, download the data yourself, or build new tools using our API.

## Authorization

This API does not require authorization.

## Actions

### Get a list of all datasets.

*Tags:* `data`

### Get metadata for this dataset.

*Tags:* `hmda`

### Get information about a particular concept in this dataset.

*Tags:* `hmda`

#### Input Parameters
* `concept` - _required_ - Name of concept

### Query a slice in this dataset.

*Tags:* `hmda`

#### Input Parameters
* `slice` - _required_ - Name of slice
* `$select` - _optional_ - Fields to return, separated by commas.
* `$where` - _optional_ - Conditions to search for in the slice, in SQL WHERE style.
* `$group` - _optional_ - Fields to group by, summarizing the data, separated by commas.
* `$limit` - _optional_ - Number of records to return, 100 by default. Enter 0 for no limit.
* `$offset` - _optional_ - Number of records to skip.
* `$orderBy` - _optional_ - Fields to order by, separated by commas. ASC and DESC can be used to modify the order.
* `$callback` - _optional_ - JavaScript callback to invoke. Only useful with JSONP requests.

### Get the metadata for a slice in this dataset.

*Tags:* `hmda`

#### Input Parameters
* `slice` - _required_ - Name of slice

### Get metadata about a dataset.

*Tags:* `data`

#### Input Parameters
* `dataset` - _required_ - Name of dataset

## License

**flow**ground :- Telekom iPaaS / consumerfinance-gov-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
