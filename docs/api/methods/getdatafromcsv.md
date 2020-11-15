---
title: GetDataFromCSV
parent: Methods
grand_parent: API
nav_order: 6
---

# GetDataFromCSV
{: .fs-9 }

Dumps a CSV file content to a string variable
{: .fs-6 .fw-300 }

---

## Syntax

*expression*.`GetDataFromCSV`*(csvPathAndFilename)*

### Parameters

The required *csvPathAndFilename* argument is an identifier specifying a `String` Type variable.

### Return value

*Type*: `String`

>📝**Note**
>{: .text-grey-lt-000 .bg-green-000 }
>The *csvPathAndFilename* parameter must be the full path to the target CSV file, this means, the parameter holds the folder path, the file name and the ".csv" extension.
{: .text-grey-dk-300 .bg-grey-lt-000 }

## Behavior

The `GetDataFromCSV` method returns an empty `String` when errors occurs.

[Back to Methods overview](https://ws-garcia.github.io/VBA-CSV-interface/api/methods/)