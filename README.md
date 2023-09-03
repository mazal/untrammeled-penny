untrammeled-penny ⬩ DEMO: a trial using blockquote w/in lists
===================

While attempting routine documentation in Markdown, a number of **edge cases** presented themselves. In essence, this "README.md" file is faux or trial README, using a number of the edge-cases encountered, namely: Nesting a blockquote w/in list element; Nesting a list w/in blockquote element; Deploying footnotes (understanding footnotes, while simply starting to make use of them!); Strikethrough; Old style title line (?).

## Contained in This Document
- Example 1: Nested blockquote w/in list element
- Example 2: Nested list w/in a blockquote element
- Example 3: Nested list w/in blockquote (poor markdown)
- Example 4: footnote sample
- Example 5: footnote sample
- Notes: troubleshooting, tips, & quirks
- Tools used
- Resources


## Samples

### Example 1: Nested Blockquote w/in list element[^1]
* Top Level
    * Integration
      1. YAML (in conjunction with Markdown)
         > YAML—often used for configuration files—stands for yet another markup language, or YAML ain’t markup language, emphasizing YAML is for data, not documents. It’s designed to be easy to read and understand and can be used in conjunction with other programming languages due to its flexibility and accessibility.
      1. Jekyll  

### Example 2: Nested list w/in a blockquote element[^2]
“You write it like this— ”

> For example:
>
> - Trust Level
> - Confidence in advice given
> - Formal vs. informal relationship
> - Things you talk about

### Example 3: Nested list w/in blockquote (poor markdown)[^3]

“I'm guessing what you did was start the bullets after the 
‘For example,’ with a single line break rather than a double break— ”  

> For example:
> - Trust Level
- Confidence in advice given
- Formal vs informal relationship
- Things you talk about

### Example 4: footnote sample[^4]

### Example 5: footnote sample[^5]

## Notes: troubleshooting, tips, & quirks

MacDown shows odd, non-conforming, and unexpected output, compared to MacDown, for example.

- ~~Footnotes are broken down into text, followed by numbered list. However, nubmbered holds no content.~~  [EDIT: 🧰 Fixed!! Add space between colon and text (at the extended footnote.)]

## Tools used

- Markdown (GitHub Flavored[^6]; CommonMark[^7])
- MacDown
- Marked2
- GitHub.com (specifically the Markdown Edit/Preview function available in each repo)
- Vivaldi
- Zettlr
- untrammeled-penny repo[^8]

## Resources

[^1]: Some text.

[^2]: Answer by [Catija (2020)](https://meta.stackexchange.com/questions/348274/blockquotes-should-be-formatted-to-support-bullet-points-and-numbered-lists), staff/moderator meta.stackexchange.com.

[^3]: Catija (2020) (example of poor markdown)

[^4]: [Catija (2020)](https://meta.stackexchange.com/questions/348274/blockquotes-should-be-formatted-to-support-bullet-points-and-numbered-lists)

[^5]: Text2

[^6]: [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

[^7]: [CommonMark](https://commonmark.org)—A strongly defined, highly compatible specification of Markdown.

[^8]: [untrammeled-penny](https://github.com/mazal/untrammeled-penny) at GitHub
