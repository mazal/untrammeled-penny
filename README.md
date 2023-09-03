# DEMO: trial of a blockquote w/in a list ⬩ untrammeled-penny

While attempting routine documentation in Markdown, a number of **edge cases** presented themselves. In essence, this "README.md" file is faux or trial README, using a number of the edge-cases encountered, namely: **Nesting a blockquote** w/in list element; **Nesting a list** w/in blockquote element; Deploying footnotes (understanding footnotes, while simply starting to make use of them!); Strikethrough; Old style title line (?).

## Contained in This Document
- Title
- Introduction
- Samples
  - Nested blockquote w/in list element (Example-1)
  - Nested list w/in a blockquote element (Example-2)
  - Nested list w/in blockquote (poor markdown) (Example-3)
  - footnote (Example-4)
- Troubleshooting:
    - Bugs, Tips & Quirks —
    - Notes —
    - Notes: further research —
- Tools used
- Resources

## Samples

### Example 1: Nested Blockquote w/in list element
* Top Level
    * Integration
      1. YAML (in conjunction with Markdown)
         > YAML—often used for configuration files—stands for yet another markup language, or YAML ain’t markup language, emphasizing YAML is for data, not documents. It’s designed to be easy to read and understand and can be used in conjunction with other programming languages due to its flexibility and accessibility.
      1. Jekyll  

### Example 2: Nested list w/in a blockquote element[^1]
“You write it like this— ”

> For example:
>
> - Trust Level
> - Confidence in advice given
> - Formal vs. informal relationship
> - Things you talk about

### Example 3: Nested list w/in blockquote (poor markdown)[^2]

“I’m guessing what you did was start the bullets after the 
‘For example,’ with a single line break rather than a double break—”  

> For example:
> - Trust Level
- Confidence in advice given
- Formal vs. informal relationship
- Things you talk about

### Example 4: footnote sample[^3]

## Troubleshooting

### Bugs, Tips & Quirks —

MacDown shows odd, non-conforming, and unexpected output compared to Marked2, for example.

- ~~Footnotes are broken down into text, followed by a numbered list. However, nubmbered holds no content.~~  [EDIT: 🧰 Fixed!! Add space between colon and text (at the extended footnote.)]
- SEE: Notes section (following) for breakdown of today’s problematic encounters (almost entirely resolved.)
    - MacDown continues to render nested blockquotes unpredictably (post woohoo.) However, after employing GitHub edit/preview feature, I feel confident with the final sample’s syntax.

### Notes — WILT Summary

The tremendous and varied Markdown implementations that exist in the field should be made clear. This led to confusion and frustration as I started. Particularly in testing new ideas, the inconsistent rendering left me feeling helpless. It stopped my ability to absorb even the basics of what otherwise should be a streamlined, get-to-work language. 

After research and due diligence, I see CommonMark[^4] and GitHub flavored[^5] as essential and widely used implementations. CommonMark seemed intent on a consortium to determine standards, led by a top-flight corps of volunteer engineers, ranging from the cream of Stack Overflow/Exchange to GitHub, Pandoc, Reddit, et al. However, their last “Spec” seems to have been developed two years ago, in 2021, and none has been formally published afaik.[^6] ‼️ MultiMark is yet another seemingly **important Markdown branch** I should document.

I enjoy using MacDown Editor with Marked2 parser/renderer/previewer (oy!), plus Zettlr for organizing attribuion. However, each new Markdwon concept, particularly newer elements, was generating confusion—not understanding if inconsistencies or unexpected behavior was due to user error (me) or differences in parsing engine or settings, on and on. The helpful (and excellent) tool, Babelmark 3[^7] by Alexandre Mutel [^8], renders a comparison of over 250+ (‼️ cite?) Markdown “converts servers,” along with relevant information attached to each run. It is a fantastic tool. Nonetheless, the “noise” of many instances and a very reasonable 1000-line limit limit the tool for day-to-day production use. 

After much trial and error, I’ve settled on my stash of GitHub repos to demo and test run final `.md` files—especially READMEs. I am confident that what renders well on GitHub will conform and render well in most spaces where I want these files to be hosted. In fact, after cleaning up my “tests” here on GitHub and pasting them back into my local directories, both MacDown and Marked2 behave beautifully in _EVERY SINGLE edge case!_ 🎉 (err, well most.. woohoo!)

GitHub (for now) is not the ideal space to build a _starter_ developer house. It’s powerful while streamlined.. and yet daunting (to me, rn). On the other hand, as a repository of `.md` files, GitHub is perfect! I can’t get into too much trouble posting READMEs 😳. I’m excited to start my coding journey, knowing I have a safe place to test and host documentation–the lifeblood of the student.

#### NOTES: Further research —
   - Document history of Markdown.
   - Note Markdown’s current status.
   - Chronicle VIPs in the field.

## Tools used

- Markdown (GitHub Flavored; CommonMark)
- MacDown
- Marked2
- Zettlr
- Babelmark 3
- GitHub.com (specifically Markdown Edit/Preview function)
- untrammeled-penny repo[^9]
- Vivaldi
- MacOS Ventura, 13.5.1; MacBookPro 2023, M2 Max

## Resources

[^1]: Answered by [Catija (2020)](https://meta.stackexchange.com/questions/348274/blockquotes-should-be-formatted-to-support-bullet-points-and-numbered-lists); Staff/moderator at Meta.stackexchange.com.

[^2]: Catija (2020) (example of poor Markdown).

[^3]: [Catija (2020)](https://meta.stackexchange.com/questions/348274/blockquotes-should-be-formatted-to-support-bullet-points-and-numbered-lists).

[^4]: [CommonMark](https://commonmark.org)—A strongly defined, highly compatible specification of Markdown.

[^5]: GitHub Flavored Markdown [Spec](https://github.github.com/gfm/).

[^6]: CommonMark [Spec](https://spec.commonmark.org).

[^7]: [Babelmark 3](https://babelmark.github.io). NOTE: Babelmark 1 & Babelmark 2 were developed and maintained by previous VIPs — ‼️ Document history.

[^8]: [Alexandre Mutel](http://xoofx.com)'s personal website.

[^9]: [untrammeled-penny](https://github.com/mazal/untrammeled-penny) repo at GitHub.

