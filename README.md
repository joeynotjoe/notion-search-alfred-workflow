# notion-search-alfred-workflow
An Alfred workflow to search Notion with instant results

Simply type your keyword into Alfred (default: ns) to see instant search results from Notion that mimic the Quick Find function in the Notion webapp. Selecting a search result takes you to that page in Notion in your default web browser.

## Workflow Variables

- `cookie`: Needed for your Notion token. I don't know how long this until a Notion token expires but at least 5+ days, I haven't used it long enough yet to quantify how long.
- `notionSpaceId`: Your organisation identifier. 

## Obtaining your workflow variables

Visit the Notion webapp and use your browser developer tools to see the network requests being made when you type in anything to the quick find search bar.

Here you'll see a request called 'search', check the request headers to copy the `cookie` value and check the request payload to copy your `notionSpaceId`.

## Download:
https://github.com/wrjlewis/notion-search-alfred-workflow/raw/master/Notion%20Search.alfredworkflow

## Forum topic: