# Free Acorns

This is a loose organization that allows members to experiment with GitHub to create, maintain, fork, merge, and even publish Open Educational Resources. 

At this point, membership of this organization is by individual approval or invitation. If you are interested in joining this organization, please email Tak Auyeung first.

For member general discussions, please use the [organization discussions](https://github.com/orgs/Free-acorns/discussions).

## What is Free Acorns about?

Free Acorns is a GitHub organization to house repositories and projects related to OER efforts. Participation is strictly individual and by choice. There is no institution involvement.

Free Acorns has two primary objectives. The one is to actually house OER content. GitHub has a reasonable renderer of [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), and GitHub also supports a web-based editor/previewer for Markdown files. This lowers the energy barrier to get started with OER authoring, cloning, and forking.

The other primary objective of Free Acorns is to examine the feasibility of using GitHub to organize OER content in an organization scale (versus a personal scale).

## How the use of GitHub aligns with OER

GitHub is not just a platform originally intended for revision control of source code based on a tool set called `git`. `git`, like its predecessors, such as `cvs`, `git` facilitates a few key actions:

* Clone: to copy a version of a repository to a local computer.
* Commit: to mark a number of files as revised.
* Push: to locally committed files to the repository.
* Pull: to integrate changes made to a repository to a local copy that is being revised.
* Fork: to create a new branch of a repository, each branch has its own series of versions.
* Join: to merge two branches into one, integrating the revisions.

Of course, this is just a superficial summary of the key actions of `git`. These actions are important to a self-sustaining community of OER participants:

* Clone: allows anyone who is interested to "get a copy of the OER material." This includes not only the published content, but also all the "source" material that is needed to create the published content.
* Commit: Anyone who has cloned a specific OER repository can make local changes and create revised published content, and continue to use `git` locally to keep track of revisions.
* Push: When local changes are completed, these changes are reflected in the repository, so all new clones will have the revisions incorporated. However, this action also allows other clones to "pull" the revisions to integrate into local revisions.
* Pull: A clone that is already being revised can incorporate the "latest and greatest" revisions of the repository.
* Fork: An author can take a repository in a different branch and make a spinoff.
* Merge: Authors of branches can collaborate and integrate different branches back into a single branch that incorporates revisions of the branches being merged.

These actions allow a community of OER authors, users, and collaborators to leverage work that has been done, contribute edits and new content, diversify, specialize, and collaborate without the need to conform. In a way, this enables the organic Darwinian approach as well as the engineering approach. Every member of an OER community can choose what to do, and yet at the same time collaborate.

# The GitHub approach compared to [LibreTexts](https://libretexts.org)

## The purpose of each platform

GitHub is intended as a revision control mechanism for cloud-hosted repositories of (programming) source code files. LibreTexts, on the other hand, is intended to be a one-stop solution for OER material, including content as well as activities.

Both platforms support the publication of material as well as the "remix" (in LibreTexts terms) or "fork and join" (in `git` terms) of content. 

## The implied structure of each platform

LibreTexts has an underlying assumption that OER content is in a "book" format. This enables LibreTexts to offer the "print as a book" feature in case prints are necessary.

GitHub only has one implied structure: folders. In other words, there is no implied structure other than the folder structure that is identical to how computer users organize files in folders.

## What it takes to start authoring and editing

LibreTexts utilizes a web-based WYSIWYG editor that can also deep-dive into the actual HTML code. This means just about anyone can start authoring and editing content. 

GitHub has a web-based editor for text files, and a preview feature to render Markdown files. GitHub does not have any built-in WYSIWYG editor. An OER author or editor needs to learn Markdown in order to create or edit content. Markdown is a fairly straightforward mark-up language, but there is a learning curve.

## Support of activities

LibreTexts intends to support interactive activities.

GitHub as a platform does not support interactive activities. However, JavaScript embedded in HTML documents can be used for client-side interaction.

## Integration into LMSes

LibreTexts intends to support LMS integration.

GitHub does not support LMS integration. Because resources in GitHub have URLs, an LMS can point to GitHub content as external links.

# Is the GitHub approach suitable for me?

It depends. As a platform, LibreTexts is a better OER platform for most OER authors and collaborators.

The GitHub approach, on the other hand, is a platform worthy of consideration for OER authors and collaborations who diverge in one or more of the following ways:

* A preference to choose and use their own tools to edit and otherwise process content material.
  * Installed editors like `vi`, `vim`, and `nvim` are efficient and flexible. There are plenty of extensions to enhance the editing of text.
  * `pandoc` is a tool that can be used to convert file formats with extensions to expand the capabilities. The use of `pandoc` can extend Markdown to express graphs, charts, etc.
* A different way to organize OER content.
  * *For example:*
    * Instead of using a book-like linear organization, use a mesh-like dependency-based structure.
    * Each individual content module is relatively short, addressing a topic that is worth no more than 2 to 3 lecture hours.
    * Each module contains prerequisite links to other modules that cover the prerequisite knowledge, concepts, skills, definitions, etc.
* Different ways to generate activities and assessments.
  * *For example:*
    * The use of subject-specific custom scripts to generate assessment questions.
    * The use of Google App Script in conjunction with Google Doc or Google Sheet to generate practice activities.

# FAQs

* Do I have to use Markdown for my content?
  * No. GitHub can work with any type of file. However, text files (such as HTML, Markdown, $\LaTeX$) allows change tracking, and as a result, revision control.
* I am new to Markdown, are there editor that makes it easier to work with Markdown documents?
  * Yes. There free and paid editors that make Markdown editing easier. 
