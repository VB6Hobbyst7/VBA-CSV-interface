---
title: EscapeTokens
parent: Enumerations
grand_parent: API
nav_order: 1
---

# EscapeTokens Enum
{: .fs-9 }

Provides a list of constants for use to configure the char used as escape one.
{: .fs-6 .fw-300 }

---

## Parts

|**_Constant_**|**_Member name_**|
|:----------|:----------|
|0|*NullChar*|
|1|*Apostrophe*|
|2|*DoubleQuotes*|

---

## Syntax

*variable* = `EscapeTokens`.*Constant*

>📝**Note**
>{: .text-grey-lt-000 .bg-green-000 }
>The `EscapeTokens.NullChar` value is used with the`QuotationMode.All` setting to indicates the CSV/TSV file does not use any escape char in its whole length. This values combination conduces the file to be parse/write assuming the `FieldsDelimiter` property is enough for the import/export operations.
>
>In the case the `FieldsDelimiter` property is not enough for successfully done the import/export operations, the `EscapeTokens.DoubleQuotes` value would be used for parse/write an CSV/TSV having fields to be escaped with double quote and the `EscapeTokens.Apostrophe` values for parse/write a file having fields to be escaped with the apostrophe, using the `QuotationMode.Critical` mode.
{: .text-grey-dk-300 .bg-grey-lt-000 }

See also
: [EscapeToken Property](https://ws-garcia.github.io/VBA-CSV-interface/api/properties/escapetoken.html), [QuotationMode Enumeration](https://ws-garcia.github.io/VBA-CSV-interface/api/enumerations/quotationmode.html), [FieldsDelimiter Property](https://ws-garcia.github.io/VBA-CSV-interface/api/properties/fieldsdelimiter.html).

[Back to Enumerations overview](https://ws-garcia.github.io/VBA-CSV-interface/api/enumerations/)