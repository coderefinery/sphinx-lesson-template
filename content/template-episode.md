# Episode template

:::{questions}
- What syntax is used to make a lesson?
- How do you structure a lesson effectively for teaching?
- `questions` are at the top of a lesson and provide a starting
  point for what you might learn.  It is usually a bulleted list.
:::

:::{objectives}
- Show a complete lesson page with all of the most common
  structures.
- ...

This is also a holdover from the carpentries-style.  It could
usually be left off.
:::


The introduction should be a high level overview of what is on the
page and why it is interesting.  This page demonstrates every element
you might typically find in a lesson and their typical usage.


The lines below (only visible in the source file) will set the default
highlighting language for the entire page.

:::{highlight} python
:::



## Section

A section.

:::{discussion}
Discuss the following.  This is green, so is intended to be
exercise-like (active work in the class).

- A discussion section
- Another discussion topic
:::



## Section

```
print("hello world")
# This uses the default highlighting language
```

```python
print("hello world)
```

:::::{tabs}
::::{group-tab} Python
This is a group-tab (if you flip it, all tabs on the page flip to
this)

```python
print("Hello World!")
```
::::

::::{group-tab} R
::::

:::::


## Exercises: description

:::{exercise} Exercise Topic-1: imperative description of exercise
Exercise text here.
:::

:::{solution}
Solution text here
:::


The following code-tab has each tab as a code block (there is no space
for unformatted text).

:::::{tabs}
```{code-tab} python
print("Hello World!")
# Note the tab titles need to be lowercase to max the exact lexer names.
```

```{code-tab} r
print("Hello World!")
```

:::::

:::{admonition} Advanced: topic of the box
---
class: dropdown
---
Include advanced material in a box such as this.  Depending on the
importance, it could be dropdown, or not.

The purpose of setting it off like this is to make it clear that one
does not need to focus their mental effort on this during the main
lesson, but an instructor could of course choose to talk about it
during any particular teaching event.
:::

:::{admonition} Optional: topic of the box
---
class: dropdown
---
Include optional material in a box such as this.  Depending on the
importance, it could be dropdown, or not.
:::




## Image

:::{figure} template-image-1.png
---
alt: Alt text here
---

Detailed caption goes here.  When creating images, you should consider
how other people coming after you can modify them.  Include a
modifiable source, and consider what is common enough that other
people will know how to maintain it in the future.  Also consider
making it *not* so specific to the current text, so that it doesn't
have to be updated for every text change (maintainable is better than
perfect).  Consider using the caption for changeable explanations,
instead of embedding it in the image.
.
Include alt text with the basics, but don't duplicate explination from
the text in the caption (instead say "as explained in text").
.
You should ONLY include CC-BY 4.0 or public domain images.  Include
the attribution in the image caption here.
.
Source: CC-0, machine generated random avatar
:::



## Summary

A Summary of what you learned and why it might be useful.  Maybe a
hint of what comes in the next lesson.



## See also

- Other relevant links
- Other link



:::{keypoints}
- What the learner should take away
- point 2
- ...

This is another holdover from the carpentries style.  This perhaps
is better done in the "summary" section.
:::
