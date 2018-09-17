# Contributing

## Some Rules
Whether you want to contribute via PR or issue, there are some guidelines that should be followed:
* Don't use rude or abrasive language in any text you want to be added to the document. 
    * If someone was asking you to make a change, how would you want them to ask?
* Always search through existing issues and the current document before proposing a change.
    * We don't want a bunch of people making the same requests. If you find one that is very similar to yours, you might be better off just discussing the existing one and proposing some tweaks.
* All PR/Issue titles must include the name of the item being changed, as it appears in game.
    * This is so it's easier to search through previous proposals and avoid making duplicates.

## Pull Requests

This is the most helpful method of contributing as it means that we don't have to manually put your idea into the format of this document. However, it is not necessary. If you're not comfortable with making PRs, you can skip this section and read [Issues](#issues).

### Template

There is a very particular format we're trying to adhere to, so when making PRs, please use the following template.

If you're making a contribution to a file that doesn't yet exist, copy the whole template. The filename can be anything as long as it makes sense and ends with `.md`. Make sure it's in the right folder. You will also need to add a reference to that file to the `SUMMARY.md` file in the `src` directory. The format is simple:
```markdown
[Chapter Title](relative/path/to/file.md)
```
Sub-chapters should be sorted alphabetically.

It should be pretty straightforward based on the contents already in the file, but failing all else you can just open a PR without `SUMMARY.md` and we'll help you figure it out.

If it already exists, just copy the line that has `###Contributor` and everything below it and append it to the bottom of the file.

**Always** put your idea under the Disputed Changes section.

You're also welcome to contribute additional information about the item's statistics, just include where you got that information from if it's not already cited.
```markdown
# Item Name
item's current statistics. grab any statistics you can find from the TF wiki, and cite it as your source as follows:

*Source: [TF Wiki](url of that item's wiki page)*

## Proposed Change
...

## Disputed Changes
### Contributor
your username
### Changes
any statistics that are different from stock
### Current Problems
why you think the item needs to be changed
### Explanation of Changes
why you think your changes will benefit the game
### Additional Comments
this section is optional, it's just for information that doesn't fit anywhere else.
```


## Issues

If you're not comfortable with pull requests, that's fine. You can just [open an issue](https://github.com/phxvyper/tf-rebalance/issues/new) and fill out the template below.

```
Item Name:
item name

Your username:
the username you'd like to be credited with for your idea.

Changes:
explain what about your idea is different from stock

Current Problems:
why you think the item needs to be changed

Explanation of Changes:
why you think your changes will benefit the game

Additional Comments:
anything else you want to say that doesn't fit into the above sections. this is optional.
```
