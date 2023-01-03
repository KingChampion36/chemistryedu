# Contributing to ChemistryEdu

## How To Contribute

We'd love to accept your patches and contributions to this project. There are just a few guidelines you need to follow which are described in detail below.

## Material for Mkdocs theme

We are using the Material for Mkdocs theme to style the content. See [the Material for Mkdocs reference guide](https://squidfunk.github.io/mkdocs-material/)
for full details on using the theme.

## Previewing content locally

See instructions [here](SETUP.md).

## Emoji

The PyMarkdown Emoji extension is configured for use with Material theme Twitter emojis, eg `:smile:`. For ideas see

* <https://github.com/ikatyang/emoji-cheat-sheet>
* <https://emojipedia.org/twitter>

> &#8505;️ Not all Emoji shortcodes are supported

Emoji can also be added using unicode character syntax, eg `&#128522;`

## Admonition boxes

The Mkdocs [Admonition](https://python-markdown.github.io/extensions/admonition/) extension is configured to allow nice
looking admonition boxes, eg

```markdown
!!! important
    Some important text
```

Or to customise the title,

```markdown
!!! important "Remember to do this"
    Some important text
```

The following admonition box styles can be used: `attention`, `caution`, `danger`, `warning`, `error`, `hint`,
`important`, `note`, `tip` and `question`

## Creating a pull request (PR)

Please create a PR to create/update/delete files in this repo.

The following conventions should be followed when creating markdown content
* H1 headings (`#`) should be formatted in Title Case using https://titlecase.com/
* All other headings (`##`, `###` etc) should be formatted in Sentence case using https://titlecase.com/
* Proper nouns that occur in a sentence case heading should retain their capital letters
* Asterisk characters (`*`) should be used to prefix unordered list items

Before raising a PR, please preview content changes locally to ensure they look as intended (see instructions above).

Once the PR is merged the changes will be deployed to github pages.
