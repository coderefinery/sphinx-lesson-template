# LESSON NAME

Intro - a paragraph or two broadly describing the topic of the lesson,
the audience, and why someone might need it.

This is a self-demonstrating template for sphinx-lesson.  You can copy
and modify it to create your own lesson (deleting all the template
stuff), and **you can browse it to see a self-demonstrating example of
our lesson best practices.**

:::{prereq}
prerequisites - let readers know what they need to do the typical
pathway of the lesson.  You can include mentions of what changes if
you are below that (for example get motivation but not be able to do
the exercises).

This template assumes someone already know enough Sphinx to get the
actual project set up, can manage the deployment on Github Pages (or
wherever).  These are not needed during most of the lesson process and
you can probably ask someone to help you with that.  This can be found
in the sphinx-lesson documentation or CodeRefinery documentation
lesson.

It also assumes knowledge of basic git, file editing, etc.
:::

```{csv-table}
:delim: ;
:widths: auto

20 min ; {doc}`filename`
```

```{toctree}
:caption: The lesson
:maxdepth: 1

template-intro
template-episode
template-optional-episode-inline
template-outro
```

```{toctree}
:caption: Supplementary material
:maxdepth: 1

template-optional-episode
template-advanced-episode
```


```{toctree}
:caption: Reference
:maxdepth: 1

quick-reference
guide
```

(learner-personas)=

## Who is the course for?

Several more paragraphs, possibly an intro and one per "learner
persona" and what they can expect to get.

Lesson designers can copy and use this as a base to create new
lessons.  They should already know about Sphinx (for example from the
documentation lesson) and a bit about the concept of sphinx-lesson,
though really it's normal Sphinx so copying this is sufficient.  They
should be able to learn our usual conventions.

Lesson maintainers (of existing lessons) can compare their lessons to
the design standards seen here and see what updates may need to be
done.


## About the course



## See also

* sphinx-lesson <https://coderefinery.github.io/sphinx-lesson/>
* CodeRefinery manuals, lesson development section
  <https://coderefinery.github.io/manuals/>
* CodeRefinery documentation lesson
  <https://coderefinery.github.io/documentation/> (Sphinx basics)
* 

## Credits

* rkdarst has made and maintains this for now, but contributions are welcome.
