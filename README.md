# Simple README Guide
So you want to write some documentation? This is a quick 15-minute reference guide to show you how.

## Overview

The goal of writing a README is give users of your software a place to start. READMEs are most commonly written in the markdown format (.md), and there should always be at least one at the root directory of every Git repository. By default, GitHub will render the `README.md` file on your project page (if it finds one).

#### Who is the README for?

* Your clients that hired you to write the project.
* Other team members who need to use your project.
* Contractors you might hire to audit your project.
* Random people who want to check out your project.
* And most importantly... yourself! For when you need to come back to the project and forgot how everything works.

#### What should a README have?

This can depend on the type of your project. But generally it falls into these categories.

* An overview of the project (what it does, why it exists, etc).
* A *quick-start* guide for running the project from scratch (usually step by step commands). This can include instructions to install any dependencies of the project as well.
* Architecture diagrams and images to help explain how the project works.
* Detailed explanation of the most important parts of the project.
* Any links and outside references.
* Any notable bugs, problems, solutions, etc. in the project.

## Tools

**[Typora](https://typora.io/)**: README files are normally `.md` format, so I recommend a good markdown editor. There's many available but I think this one is free and good, and available on all platforms.

**[Draw.IO](https://www.draw.io/)**: It's very common you will need graphs or diagrams in your README, especially when architecture is concerned. This one is a free, cloud based tool that literally has everything you need. After you create your diagrams, export them as `.svg`.

## Structure

Every project is different, but typically I'd structure it like follows:

1. A short overview or introduction for the project.
2. A quick-start guide to help the user set it up and run it.
3. A high-level architecture diagram or visuals (if relevant).
4. Any other relevant content.
5. References, dependencies, and short-term notes.

## Formatting

Formatting in markdown is easy, because there's not a lot you can do. You can't really choose exact font or sizes or colors. You only really get a few options. But it's really important to know what you have available, and to use it to your benefit.

### Header Weights

The easiest trick to creating structure is applying the header tags. If you right click on a text in Typora, you can select 'Paragraph,' which offers options like *Heading 1*, *Heading 2* etc. Alternatively there should be a hot-key like `Ctrl+1` to easily set the header style. Normally I only use H1 for the actual document title. I'll use H2 for section titles, and just go down from there.

### Font Styles

You have a choice between normal, **bold**, *italics*, and ***italics bold***. Use them how to see fit. Highlight anything important. Don't be boring.

### Bullets

* When you need to make a list of things, use bullet points.
* Look how much easier it is to read!

- [ ] Alternatively, you can also include check-boxes for 'to-do' style lists.
- [ ] And again!

### Tables

Usually when you have to arrange data in a more organized format, use a table.

| Technology | Description |
| ---------- | ----------- |
| NodeJS     | Back End    |
| React      | Front End   |

### Code

When you have to include code in your README, use the back-tick (`) to surround it.

Single back-tick will format code on the same line: `example`.

Triple back-tick will create a code block:

```bash
hello world
```

You can also edit the block format so that it can color it according to your language (bash, javascript, etc).

## Conclusion

That's all you need to get started! Check out this [awesome repo of curated READMEs](https://github.com/matiassingers/awesome-readme) for more examples, guides, and tools.

