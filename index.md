---
layout: lesson
---

This tutorial is intended for researchers who would like to use [version control]({{ page.root }}/reference#version-control) to
manage their work. Version control is better than mailing files back and forth:

*   Nothing that is committed to version control is ever lost, unless
    you work really, really hard at it. Since all old versions of
    files are saved, it's always possible to go back in time to see
    exactly who wrote what on a particular day, or what version of a
    program was used to generate a particular set of results.

*   As we have this record of who made what changes when, we know who to ask
    if we have questions later on, and, if needed, revert to a previous
    version, much like the "undo" feature in an editor.

*   When several people collaborate in the same project, it's possible to
    accidentally overlook or overwrite someone's changes. The version control
    system automatically notifies users whenever there's a conflict between one
    person's work and another's.

Teams are not the only ones to benefit from version control: lone
researchers can benefit immensely.  Keeping a record of what was
changed, when, and why is extremely useful for all researchers if they
ever need to come back to the project later on (e.g., a year later,
when memory has faded).

Version control is the lab notebook of the digital world: it's what
professionals use to keep track of what they've done and to
collaborate with other people.  Every large software development
project relies on it, and most programmers use it for their small jobs
as well.  And it isn't just for software: books,
papers, small data sets, and anything that changes over time or needs
to be shared can and should be stored in a version control system.

> ## Prerequisites
>
> In this lesson we learn how to use Git by using the [GitHub Desktop](https://desktop.github.com/) client and the [Atom](https://atom.io/) text editor.
> You will need to install both of these applications before starting.
> You will also need to sign up for a GitHub account using the instructions [here](https://help.github.com/en/github/getting-started-with-github/signing-up-for-a-new-github-account) if you do not have one already.  We will also go over how to do this during the lesson.
> No previous experience with a command line interface is necessary.
>
{: .prereq}

> ## Formatting Notes
>
> The following formatting conventions are used in this lesson:
>
> *Italics* are used to indicate elements of a graphical interface, such as
> buttons, dropdowns, or labelled panes.  In cases where there is a named field,
> _**bold italics**_ indicate the field and regulary *italics* indicate the value
> that field should take.
>
> `Block text` indicates folder names, file names, Git-specific ways to
> refer to a copy of a file, and code written in a programming language.
>
> Hyperlinks are used to link new definitions back to the [glossary]({{ page.root }}{% link reference.md %}).
>
> <kbd>Keyboard key</kbd> formatting indicates keys that must be pressed to access some functionality in the GitHub Desktop client.
>
{: .callout}
