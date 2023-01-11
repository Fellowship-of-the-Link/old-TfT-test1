# Site review 2023-01-10, Pete

I'm doing a review of the site, partly for the "Check/Complete" tasks in the task tracker, and partly with the idea to generally tidy up the site.

Some thoughts:
- use consistent capitalization for pages
	- tools and practices may have separate rules?
- use ISO 8601 date format
- use hashtags consistently
	- see the Tags pane
- pro tip: consistency is achieved by writing down rules in the style guide (in consultation and discussion with all the participants)
- delete pages that aren't really being used (empty, deprecated, etc.)
- resolve the "front of house / back of house" issue, either by having two separate wikis (probably better), or by using something else like simple namespaces for each
- move `data` files to `_attachments`
- move `files` pages to root, get rid of `files` folder
- move `project` pages to root, get rid of `project` folder
- see "Repatterning page titles and tags" below

## Repatterning page titles and tags

At the top of pages, rather than:

```
#tool: #pocket
```

(tag: tag)

I suggest:

```
# Pocket

#tool
```

(page title / tag)