# 404 page process
## Problem statement
People will include new tools and techniques in their people profiles. When rendered into HTML, these point to pages which don't exist. Visitors following the link will see a 404.

## Possible Solutions 
### Automated template-driven page creation
Whenever a page is uploaded with a link to a non-existent page (for example, "tool5"), that page is created (eg tool5.md) using a template. 

The template is similar to the [[technique template]], in that is includes:
* title (tool5)
* description: this simply includes a short text explaining that this page is missing a description and type ("is it a tool? is it a template?)", so volunteers are welcome to contribute one (see [[How to contribute]]).
* People using this: will include, by definition, an except from all the people who submitted a profile mentioning the new tool or technique. These are the people who should be asked first to submit a description, and define its type.

### A better 404 page
At the vey least, the 404 page should:
* explain why the page is missing 
* suggest the visitor read [[How to contribute]] and contribute a description
* provide a download link for the .md file
