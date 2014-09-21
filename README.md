# RSS Parser

A Polymer rss feed parser.

## Usage

```html
<rss-feed-parser url="https://example.com/feed.xml" on-feed-parsed="{{handleResponse}}"></rss-feed-parser>
```

### Attributes

**url** - The url of the RSS feed.<br>
**auto** - If true, automatically performs an Ajax request when either url or params changes.<br>
**headers** - HTTP request headers to send.<br>
**params** - Parameters to send to the specified URL, as JSON.

### Events

**feed-parsed** - Fired when the feed has been parsed.<br>
**invalid-feed** - Fired if it is not a valid RSS feed.
