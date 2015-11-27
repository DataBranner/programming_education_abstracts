## If you'd like to contribute content

**Please**

 1. Do so as a pull request. First, [fork](https://help.github.com/articles/fork-a-repo/) the repository, add your content, and then send a pull request.
 1. Limit yourself to five abstracts per pull request, as that will keep my workload manageable.
 1. Attentively follow the formatting instructions below.
 1. Include only published author, title, highlight, and abstract content from the primary research report, rather than anything from secondary reports about the research, unless the original report is not publicly accessible.
 1. Don't add comments. The point of this project is to enable review of abstracts.

**Format**:

 1. Every abstract should be in its own Markdown file (I am technically using GitHub Flavored Markdown, [GFM](https://help.github.com/articles/github-flavored-markdown/), although [standard Markdown syntax](https://daringfireball.net/projects/markdown/syntax) acounts for most of what I actually use). Filenames should end in `.md`.
 1. The file should open with a link to the original, publicly accessible abstract file. Then include any bullet-pointed "highlights", followed by the abstract. Highlights and abstract are preceded by the words Highlights and Abstract, bold-faced. Here is a rough template:


    ```md
    [author(s) year, "title"](http://link):
    
    > **Highlights**
    > 
    > * first highlight
    > * second highlight
    > etc.
    >
    > **Abstract**
    >
    > abstract goes here
    
    [end]
    ```
    
    I normally always end a text file with `[end]`, so that there is no doubt that it has not been truncated.
 
 1. The filename should be the same content as the author, year, and title, except without double quotes around the title. Filenames should end in `.md`.
 1. Do not put a comma before the year of publication or parentheses around it.
 1. Omit a period at the end of the title. If the title ends in other punctuation (ellipsis `...`, question mark `?`, etc.), include it. Some punctuation (slash `/`, backslash `\`, colon `:`) may cause problems in some operating systems — feel free to replace with a period `.` or dash `-`.
 1. Note that many titles now have multiple parts — the first may be a question (see Gnambs, below) or end in a colon (see Grilli & Glisky, below). Be sure to include all parts of the title.
 1. Use the following formats for authors:

    2. Single-author publications. Use the surname alone.

       ```text
       Gnambs 2015, "What makes a computer wiz? Linking personality traits and programming aptitude"
       ```

    2. Institutional-author publications without identified contributers. Use the name of the project or institution, followed by "study".

       ```text
       First Steps study 2015, "Empathetic teachers enhance children's motivation for learning"
       ```

    2. Dual-author publications. Use both surnames, with `&` between them.

       ```text
       Grilli & Glisky 2015, "Imagining a Better Memory: Self-Imagination in Memory-Impaired Patients"
       ```

    2. Multiple-author publications (more than two authors). Use only the first surname, followed by `et al.`.

       ```text
       Bench et al. 2015, "Gender Gaps in Overestimation of Math Performance"
       ```

[end]
