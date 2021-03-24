# Fill the thematic gaps of Raku documentation

## The Raku Foundation

Yet Another Society, doing business as *The Raku Foundation*, has
[recently](https://github.com/Raku/Raku-Steering-Council/blob/f4c246d80b61c699e948964890fc7e0b8593d67e/minutes/20210306.md)
been constituted as "product owner" of the Raku Programming Language, to differentiate
it from the [Perl Foundation](https://perlfoundation.org), which is
the product owner of the Perl language and its ecosystem.

As a whole, Yet Another Society takes care of the Perl and Raku
languages and ecosystems, and has done so since its inception.

Raku, however, was started as "Perl 6" in the year 2000 and released
in Christmas 2015 as Perl 6.c. Perl 6, however, was a totally
different language designed from scratch in a community process, which
is why it eventually got its name changed to Raku in
October 2019. This spawned a process of a certain independence from
the sister language, which included the creation of a [Raku Steering
Council](https://raku.github.io/Raku-Steering-Council/), voted among
the community, and a recently released [Code of
Conduct](https://raku.github.io/Raku-Steering-Council/papers/CoC),
which also emerged from a community process.

The Raku Foundation thus, while inheriting the rich experience and
traditions from the Perl Foundation, will be more narrowly focused on
Raku matters, including, as is the case here, the documentation.

Yet Another Society (doing business as "The Perl Foundation") has
created, and uses in all its products, the [Artistic
License](https://opensource.org/licenses/artistic-license-2.0),
designed originally for [Perl](https://perl.org), and now extended
also to Raku and most of the products in its ecosystem.

Raku has been adopted as the language of choice by quite a few
companies and individuals, including Edument, Oetiker+Partners, and
Atikon, all of them in Europe. It's used also in several academic and
research projects. Its community is relatively small (compared to its
sister language, Perl) and diverse, and mainly meets through its [IRC
channels](https://raku.org/community) and their different
repositories. All these resources are covered by the Code of Conduct,
with the intention of making them safe spaces for everyone.

Raku documentation is a volunteer effort that emerged relatively late
in the timeline of Raku development, due mainly to the fact that it's
using its own markup language, [Pod
6](https://docs.raku.org/language/pod). Unlike other markup languages
(like, for instance, the one that inspired it, [Perl
Pod](https://perldoc.perl.org/perlpod)), it's part of the Raku language
and specified alongside it. That makes it specially stable, but
also makes it an integral part of the language, with the Raku compiler
itself also parsing and compiling this part of the documentation.

This language will be quite straightforward to learn for those that
already have familiarity with Perl, and being a markup language like
any other, will not be a strong hurdle to overcome for anyone who is
familiar with Markdown, AsciiDoc or any other such language.

## Fill (big) gaps in Raku documentation

As the rest of the Raku compilers and tools, the [Raku
documentation](https://docs.raku.org) is a volunteer effort. Although
there are a few persons, among the core developers, who are more or
less focused on it, it still needs needs not only improvement, but
enlargement in several areas.

The documentation's main mission is to be a first go-to resource for
those people that are starting to learn the language, and that, once
they're working on it, need to look up syntax or semantics of specific
parts, classes or statements. That is why there are two big areas in
it: the [language reference and
tutorials](https://docs.raku.org/language.html) section, and the
[*Types*](https://docs.raku.org/type.html) section, that works more or
less a a reference, with pages devoted to classes, methods, routines
and all the rest of the entities that form the language.

### Problem

Most tutorials are already in place, although they have missing
sections. However, there are some areas of the documentation which due
to its size (number of classes there) or simply the complexity of its
operation, have not been covered so far.

Issues related to these areas were marked as
[*big*](https://github.com/Raku/doc/issues?q=is%3Aissue+is%3Aopen+label%3Abig),
because they usually involved creating many new pages from scratch, or
creating tutorials for features that had not, so far, been documented.

It's usually the size of the task that has prevented it from being
approached by the usual cadre of volunteers, which usually focus on
issues that can be solved in a single stretch of work, or a few of
them. For instance the biggest and oldest of them is this issue that
was created almost 5 years ago on the
[`Exception`](https://github.com/Raku/doc/issues/517) types; there are
more than a hundred classes that would need to be documented,
including, in many cases, examples that would be meaningful in a
particular use case (["intent, not
syntax"](https://github.com/Raku/doc/issues/1748) is our extra-official
motto for examples.

The rest of the *big* issues vary in size, and can be set in a
descending order. In general, this is the kind of problem that we
would like the technical writer to approach.

### Scope

Within the scope of this project, the person participating in it will:

* Revise the list of *big* issues in the documentation repository,
  requesting clarifications where needed, and also prioritizing them
  in agreement with the volunteers also participating on the project.

* Initiate piece-wise work on those big issues, creating pull request
  that span at most one file. These PRs will be automatically checked
  for common pitfalls, and reviewed so that they can be improved, if
  needed. During this work, help will be available from the Raku IRC
  channels, as well as, if needed, from the group of people that are
  usually answering questions in
  [StackOverflow](https://stackoverflow.com/questions/tagged/raku).

* For the time being, documentation works in a continuous integration
  mode; anything that's admitted into the main branch is deployed,
  although sometimes not immediately. The work done by the technical
  writer will be featured in Rakudo Weekly News, as well as publicized
  within the community.

* The writer will be expected also to raise new issues that pop up in
  their exploration of the Raku language, as well as help elsewhere in
  the Raku docs site, labeling and asking for clarification in new
  issues, for instance, helping newcomers that have created their
  first PR, or work with low-hanging fruit issues elsewhere in the
  documentation.

* The writer will be also responsible for MC'ing, along volunteers, a
  doc-athon for the community to participate in editing Raku
  documentation. This will also help expand the community, and the
  writer will help onboard new people, as well as review contributions
  from complete newbies.

The volunteer stuff will be always on hand, reviewing and improving,
and helping the writer prioritize new issues, assigning it to them or
helping them through with any doubt they might have; also taking their
suggestions for more general improvements of the documentation at
large. The volunteers are people with a long experience in the
documentation, and also a proved experience with the Raku language.

### Measuring success

The first measure of success is the satisfactory closing of one or
more of the *big* issues, of course, as well as lines of (doc-as) code
written.

A secondary measure of success will be overall satisfaction with the
documentation on the part of the Raku community. Every year we produce
a survey, and one of the questions is the satisfaction with the
documentation. We'll check, using this tool, if satisfaction has
increased or not. Of course, documentation is not static and is
changing all the time, but obviously covering gaps will be one of the
main drivers of satisfaction.

Finally, the objective of the documentation is the attraction of new
programmers to the community, and new participants to the
documentation repository. A better documentation will attract more
readers, that will spend more time on it, will create new projects,
these projects will shed light on other unexplored areas of the
docspace, which will encourage people to create pull requests and
improve them. Our policy for giving new commit bits is quite liberal,
and one or two pull requests are usually enough to obtain it. So if we
manage to attract several recurring contributors to the documentation,
that will be the ultimate measure of success.

## Budget

| Budget item                        | Amount | Running total | Notes/justifications |
|------------------------------------|--------|---------------|----------------------|
| Technical writer: fill documentation gaps in the Raku docs, and work on related issues | 10000.00 | 10000.00 | Some onboarding will be necessary, and the writer needs to be paid for it. |
| Volunteer stipends                 | 1000.00| 11000 | 2 volunteer stipends x 500 each |
| Project hoodies  (10)              | 200    | 11200 | 10 hoodies for the technical writer, "official" volunteers, and other people helping. Also as doc-athon prize.

The bulk of the budget goes to the technical writer, as is
expected. Since there will be a certain amount of time needed for
onboarding, we understand the writer should be paid for it too, which
is why we have gone up to 10000$

Hoodies will go to volunteers and the writer, as well as at least 5 to
people participating (or winning a prize, depending on how many people
we have) in a hackathon.



## Additional information

As such, we have had no experience managing technical writers. JJ
Merelo has been, himself, a technical writer, having worked on the
documentation of Raku for 3 years, as well as contributed, mainly via
pull requests, to many other documentation projects. He is also the
author of two books by Apress, "Perl 6 Quick Syntax reference" and
"Raku recipes", having thus the experience of a professional editorial
workflow such as the one that was used in Apress.

He's been acting "editor" of the Raku documentation, and as such has
had the experience of reviewing most, if not all, pull requests and
also regular commits done to the documentation. We don't foresee any
major problem dealing with a technical writer, should it be funded by
Google.

<!-- Previous participation in Season of Docs, Google Summer of Code -->
<!-- or Others -->

The Perl Foundation has participated in Google Summer of Code in
several occasions, last one in 2019. We have applied for funding in
season of docs also in two occasions, the initial call in 2019 and
last year in 2020; we haven't been funded so far in this specific
call.

The Raku Foundation is under the same umbrella organization as The
Perl Foundation (known as Yet Another Society) and was only recently
recognized as such, so this is the first time it applies to Season of
Docs (or, for that matter, anything else).
