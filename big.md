*Big* issues in Raku documentation
========================

Description
-----------

Raku documentation was, from the beginning, decoupled from language
development. It started much later than language itself, and
mainly written by people not directly involved in the programming effort
itself. This essentially resulted in a de-synchronization of language
features and the documentation they would need to actually be used,
with relatively wide areas of the language uncovered, or poorly
covered, by documentation.

Issues related to these areas were marked as *big*, because they
usually involved creating many new pages from scratch, or creating
tutorials for features that had not, so far, been documented.

In this case, documentation involves good skills in reading source
code that implement features, but also proactivity requesting tests or
raising issues when the implementation is incosistent, does not behave
as expected, or untested. In general, that implies that those *big*
issues require a degree of effort that has left them, in general,
unadressed for long periods of time, as much as three years in some
cases.

The written documentation must follow a series of standards (many of
which are tested automatically), but working in these *big* issues
allow a certain degree of creative freedom; this is why this is
considered a more attractive project that small issues that need a lot
of research.

There are many other issues, however. While working on a specific
*big* issue, we would try to draw the attention of the writer to other
outstanding issued in the same area, that could maybe be solved at the
same time or with the expertise acquired solving these big
projects. Some of these issues are actually linked on the *big* issue
page, so they're not difficult to identify.



Expected outcomes
-----------------

* Document
  [`*REPO` and CUR classes](https://github.com/perl6/doc/issues/502). This
  is a set of classes which describe how modules are preprocessed, and
  how to work with them. It needs to be written from scratch.

* [Exceptions](https://github.com/perl6/doc/issues/516) are quite
  numerous, and
  mostly [undocumented](https://github.com/perl6/doc/issues/517). It
  will help if it's reorganized, a a dedicated tutorial is written
  from scratch. [Control exceptions are undocumented too](https://github.com/perl6/doc/issues/1268).

* Traits are not well documented
  either: [here](https://github.com/perl6/doc/issues/1957)
  and [here](https://github.com/perl6/doc/issues/2718), as well
  as [here](https://github.com/perl6/doc/issues/2714)
  and [here](https://github.com/perl6/doc/issues/1730).

* Some releases introduce a lot of changes when big branches are
merged. This is the case of
[2020.01](https://github.com/Raku/doc/issues/3187). There are still
quite a few tasks there that need attention.

Required skills
---------------

Required or prefered skills the person should have to be able to
tackle this project.

* Some prior experience with Raku is appreciated, but not really
  needed. Will to learn it will be a requisite. The candidate will be
  expected to be able to write, run and test short programs to be used
  as examples in the documentation.
* Good, working knowledge of English.
* Good knowledge of git and GitHub.

Rating
------

Medium.


Possible mentors
----------------

- JJ Merelo (jjmerelo@gmail.com, [GitHub](https://github.com/JJ)),
  jmerelo on Freenode.


