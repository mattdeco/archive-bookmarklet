# Archive Bookmarklet

A bookmarklet to view the [archive.ph](https://archive.ph) version of the current URL.

For a drag-to-bookmarks install UI, see the [live docs](https://mattdeco.github.io/archive-bookmarklet/).

## Installation

Bookmarklet code:

```
javascript:(function(){window.location = `https://archive.ph/submit/?url=${encodeURIComponent(window.location.href)}`})();
```

- **Desktop**: Create a bookmark and set its URL to the code above (or use the [live docs](https://mattdeco.github.io/archive-bookmarklet/) to drag the link into your bookmarks bar).
- **Mobile**: Sync desktop bookmarks, or bookmark any page, edit it, and replace the URL with the code above.

## Usage

Click or tap the bookmarklet on a page you want to view on archive.ph.

## Local preview

```
npm install
npm start
```

Opens the docs page via Parcel.
