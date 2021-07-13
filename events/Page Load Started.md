# Page Load Started

### Page Load Started is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the first event pushed in the page load event sequence.

## Javascript Code
```js
window.appEventData098 = window.appEventData098 || [];
appEventData098.push({
  "event": "Page Load Started",
    "page": {
        "hour": "<hour>",
        "isIncognitoMode": "<isIncognitoMode>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|hour|string|The time of activity at the top of the hour.||||||||
|isIncognitoMode|integer|Set on all pages when user is in "incognito mode" in their browser.||||||||
