# Crawl Properties Schema

```txt
https://schemas.w3cub.com/schemas/crawl
```

This schema is a standard for capturing pictures.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [crawl.schema.json](../generated/crawl.schema.json "open original schema") |

## Crawl Properties Type

`object` ([Crawl Properties](crawl.md))

# Crawl Properties Properties

| Property                            | Type         | Required | Nullable       | Defined by                                                                                                                                               |
| :---------------------------------- | ------------ | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)                       | `string`     | Required | cannot be null | [Crawl Properties](crawl-properties-crawl-name.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/name")                                       |
| [value](#value)                     | `string`     | Required | cannot be null | [Crawl Properties](crawl-properties-crawl-value-the-identification-of-current-crawl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/value") |
| [description](#description)         | `string`     | Required | cannot be null | [Crawl Properties](crawl-properties-crawl-description.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/description")                         |
| [type](#type)                       | `string`     | Required | cannot be null | [Crawl Properties](crawl-properties-crawl-type-json-or-html.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/type")                          |
| [category](#category)               | `boolean`    | Required | cannot be null | [Crawl Properties](crawl-properties-category.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/category")                                     |
| [categoryurl](#categoryurl)         | `string`     | Optional | cannot be null | [Crawl Properties](crawl-properties-categoryurl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/categoryurl")                               |
| [search](#search)                   | `boolean`    | Required | cannot be null | [Crawl Properties](crawl-properties-search.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/search")                                         |
| [chinesesearch](#chinesesearch)     | `boolean`    | Required | cannot be null | [Crawl Properties](crawl-properties-chinesesearch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/chinesesearch")                           |
| [categoryitem](#categoryitem)       | `object`     | Optional | cannot be null | [Crawl Properties](crawl-properties-category-item.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/categoryitem")                            |
| [categorydata](#categorydata)       | `array`      | Optional | cannot be null | [Crawl Properties](crawl-properties-category-data.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/categorydata")                            |
| [pageurl](#pageurl)                 | `string`     | Required | cannot be null | [Crawl Properties](crawl-properties-fetch-page-url.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageurl")                                |
| [pagematch](#pagematch)             | `string`     | Required | cannot be null | [Crawl Properties](crawl-properties-fetch-target-match.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pagematch")                          |
| [pagemethod](#pagemethod)           | `string`     | Optional | cannot be null | [Crawl Properties](crawl-properties-pagemethod.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pagemethod")                                 |
| [pageoffset](#pageoffset)           | `string`     | Optional | cannot be null | [Crawl Properties](crawl-properties-pageoffset.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageoffset")                                 |
| [pageoffsetmatch](#pageoffsetmatch) | `string`     | Optional | cannot be null | [Crawl Properties](crawl-properties-pageoffsetmatch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageoffsetmatch")                       |
| [searchurl](#searchurl)             | `string`     | Optional | cannot be null | [Crawl Properties](crawl-properties-searchurl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/searchurl")                                   |
| [searchmatch](#searchmatch)         | `string`     | Optional | cannot be null | [Crawl Properties](crawl-properties-searchmatch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/searchmatch")                               |
| [pageitem](#pageitem)               | `object`     | Required | cannot be null | [Crawl Properties](crawl-properties-page-item.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem")                                    |
| [useragent](#useragent)             | Unknown Type | Optional | cannot be null | [Crawl Properties](crawl-properties-fetch-useragent-or-false.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/useragent")                    |
| [headers](#headers)                 | `object`     | Optional | cannot be null | [Crawl Properties](crawl-properties-extend-fetch-headers.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/headers")                          |

## name




> Crawl Name, commonly titlecase
>

`name`

-   is required
-   Type: `string` ([Crawl name](crawl-properties-crawl-name.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-crawl-name.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/name")

### name Type

`string` ([Crawl name](crawl-properties-crawl-name.md))

## value




> Crawl type, commonly lowercase
>

`value`

-   is required
-   Type: `string` ([Crawl value, the Identification of current crawl](crawl-properties-crawl-value-the-identification-of-current-crawl.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-crawl-value-the-identification-of-current-crawl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/value")

### value Type

`string` ([Crawl value, the Identification of current crawl](crawl-properties-crawl-value-the-identification-of-current-crawl.md))

## description




> Crawl description
>

`description`

-   is required
-   Type: `string` ([Crawl description](crawl-properties-crawl-description.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-crawl-description.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/description")

### description Type

`string` ([Crawl description](crawl-properties-crawl-description.md))

## type




`type`

-   is required
-   Type: `string` ([Crawl type json or html](crawl-properties-crawl-type-json-or-html.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-crawl-type-json-or-html.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/type")

### type Type

`string` ([Crawl type json or html](crawl-properties-crawl-type-json-or-html.md))

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | ----------- |
| `"json"` |             |
| `"html"` |             |

## category




`category`

-   is required
-   Type: `boolean`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-category.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/category")

### category Type

`boolean`

## categoryurl




`categoryurl`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-categoryurl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/categoryurl")

### categoryurl Type

`string`

## search




`search`

-   is required
-   Type: `boolean`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-search.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/search")

### search Type

`boolean`

## chinesesearch




`chinesesearch`

-   is required
-   Type: `boolean`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-chinesesearch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/chinesesearch")

### chinesesearch Type

`boolean`

## categoryitem




> category item content match
>

`categoryitem`

-   is optional
-   Type: `object` ([category item](crawl-properties-category-item.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-category-item.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/categoryitem")

### categoryitem Type

`object` ([category item](crawl-properties-category-item.md))

## categorydata




> directly provide category data
>

`categorydata`

-   is optional
-   Type: `object[]` ([category data item](crawl-properties-category-data-category-data-item.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-category-data.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/categorydata")

### categorydata Type

`object[]` ([category data item](crawl-properties-category-data-category-data-item.md))

## pageurl




`pageurl`

-   is required
-   Type: `string` ([fetch page url](crawl-properties-fetch-page-url.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-fetch-page-url.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageurl")

### pageurl Type

`string` ([fetch page url](crawl-properties-fetch-page-url.md))

## pagematch

fetch page json or html target match


`pagematch`

-   is required
-   Type: `string` ([fetch target match](crawl-properties-fetch-target-match.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-fetch-target-match.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pagematch")

### pagematch Type

`string` ([fetch target match](crawl-properties-fetch-target-match.md))

## pagemethod




`pagemethod`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pagemethod.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pagemethod")

### pagemethod Type

`string`

## pageoffset




`pageoffset`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pageoffset.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageoffset")

### pageoffset Type

`string`

## pageoffsetmatch




`pageoffsetmatch`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-pageoffsetmatch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageoffsetmatch")

### pageoffsetmatch Type

`string`

## searchurl




`searchurl`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-searchurl.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/searchurl")

### searchurl Type

`string`

## searchmatch




`searchmatch`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-searchmatch.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/searchmatch")

### searchmatch Type

`string`

## pageitem




> page item content match
>

`pageitem`

-   is required
-   Type: `object` ([page item](crawl-properties-page-item.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-page-item.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/pageitem")

### pageitem Type

`object` ([page item](crawl-properties-page-item.md))

## useragent




`useragent`

-   is optional
-   Type: any of the folllowing: `string` or `boolean` ([fetch useragent or false](crawl-properties-fetch-useragent-or-false.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-fetch-useragent-or-false.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/useragent")

### useragent Type

any of the folllowing: `string` or `boolean` ([fetch useragent or false](crawl-properties-fetch-useragent-or-false.md))

## headers




`headers`

-   is optional
-   Type: `object` ([extend fetch headers](crawl-properties-extend-fetch-headers.md))
-   cannot be null
-   defined in: [Crawl Properties](crawl-properties-extend-fetch-headers.md "https&#x3A;//schemas.w3cub.com/schemas/crawl#/properties/headers")

### headers Type

`object` ([extend fetch headers](crawl-properties-extend-fetch-headers.md))
