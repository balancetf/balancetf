# Contributing

## Preface
As stated in the foreword, the goal of this document is to be as unbiased as possible. That said, we'll probably be accepting most PRs for changes *that are reasonable*. If the general consensus of a proposed change is "that's absolutely ridiculous," it may be declined or removed later if it has been added already.

## Some Rules
Whether you want to contribute via PR or issue, there are some guidelines that should be followed:
* Don't use rude or abrasive language in any text you want to be added to the document. 
    * If someone was asking you to make a change, how would you want them to ask?
* Always search through existing issues and the current document before proposing a change.
    * We don't want a bunch of people making the same requests. If you find one that is very similar to yours, you might be better off just discussing the existing one and proposing some tweaks.
* All PR/Issue titles must include the name of the item being changed, as it appears in game.
    * This is so it's easier to search through previous proposals and avoid making duplicates.
* Currently, we're only dealing with existing items. We won't accept PRs about ideas for new unlocks. We also won't accept PRs about changes to things like gamemodes, maps, etc. (though we plan to do so later)

## Pull Requests

This is the most helpful method of contributing as it means that we don't have to manually put your idea into the format of this document. However, it is not necessary. If you're not comfortable with making PRs, you can skip this section and read [Issues](#issues). Otherwise, it's best to be familiar with [Github Markdown](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf).

### Template

**Always** put your idea under the Disputed Changes section. The goal of this document is to get the attention of Valve, and the Proposed Change section is reserved for changes that have been thoroughly reviewed and we definitely want to push for.

There is a very particular format we're trying to adhere to, so when making PRs, please use the following template.

If you're making a contribution to a file that is currently empty, copy the entire template.

For item statistics, please use tables as shown in the template. If you're a bit lazy you can use this [table generator](https://ozh.github.io/ascii-tables/). Just make sure you have the output style set to Github Markdown.

You also need to check if the page you're editing exists in `src/SUMMARY.md`. If it doesn't, add it in the appropriate location like so:
```markdown
[Chapter Title](relative/path/to/file.md)
```
Sub-chapters should be sorted alphabetically.

It should be pretty straightforward based on the contents already in the file, but failing all else you can just open a PR without `SUMMARY.md` and we'll help you figure it out.

If the file you're contributing to already has content, only copy the line containing `###Contributor` and all of the lines below it.

You're also welcome to contribute additional information about the item's statistics, just include where you got that information from if it's not already cited.

PR Template:
```markdown
# Item Name
item's current statistics. grab any statistics you can find from the TF wiki, like so:
| Damage                  |        |
|-------------------------|-------:|
| Type                    | Bullet |
| Base (uncharged)        |     50 |
| Crit (uncharged)        |    150 |
| Mini-crit (uncharged)   |     68 |
...etc
your table doesn't have to look this nice, but it would be nice. it is much easier if you use a table generator like the one linked above

*Source: [TF Wiki](url of that item's wiki page)*

## Proposed Change
...

## Disputed Change #x
where x is the number of the previous change +1. obviously, first one is #1.

### Changes from Stock
any statistics that are different from the stock item that goes in this slot. NOT changes from the item's current state if it is non-stock.

### Current Problems
why you think the item needs to be changed

### Explanation of Changes
why you think your changes will benefit the game

### Additional Comments
this section is optional, it's just for information that doesn't fit anywhere else.

*Contributors: username1, username2, etc.*
replacing usernameX with the usernames of any people you want to credit for the idea, including yourself.
```
Once you've got this all filled out, it's good to run it through a [markdown preview](https://jbt.github.io/markdown-editor/) to make sure there aren't any glaring formatting issues.

## Issues

If you're not comfortable with pull requests, that's fine. You can just [open an issue](https://github.com/phxvyper/tf-rebalance/issues/new/choose) and fill out the template labeled "New Change Proposal."

