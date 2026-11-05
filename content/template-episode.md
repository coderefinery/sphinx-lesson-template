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
Discuss the following.

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



## Summary

A Summary of what you learned and why it might be useful.  Maybe a
hint of what comes next.



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
