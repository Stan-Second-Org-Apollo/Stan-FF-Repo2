# Onsite Search Performed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData098 = window.appEventData098 || [];
appEventData098.push({
  "event": "Onsite Search Performed",
    "onsiteSearch": {
        "location": {
            "radius": {
                "unitOfMeasure": "<unitOfMeasure>"
            }
        }
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|unitOfMeasure|string|The unit of measurement|miles, kilometers, meters|||||||
