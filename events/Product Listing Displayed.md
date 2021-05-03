# Product Listing Displayed

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Product Listing Displayed",
    "listingDisplayed": {
        "filterList": "<filterList>",
        "filterListLength": "<filterListLength>",
        "listingContext": "<listingContext>",
        "listingDriver": "<listingDriver>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|filterList|string|A twice delimited string of filterType and filterValue pairs.  Use ~ between type and value.  Use | between pairs|sort~price ascending|color~green|size~medium|||||||
|filterListLength|integer|The number of filterValue pairs in the filterList|0, 20, 12||||0|||
|listingContext|string|Describes the context of a listing display (sort changed, filter added, filter removed)|Filter Added, Filter Removed, Sort Change, Pagination|||||||
|listingDriver|string|Describes the action that caused the listing to be displayed|Onsite Search, Curated Assortment, Navigation|||||||
