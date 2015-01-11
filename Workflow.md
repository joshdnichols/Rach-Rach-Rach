Workflow
========

How I would like to work is as simply as possible. There are a lot of
complicated things going on in the score (including the accompaniment!), and I
want to avoid encumbering upon what remains to poorly designed workflow.

Suffice it to say, the particular edition referenced in the README should be the
base-model for our notes. There are many “rehearsal marks” contained in the
accompaniment - that shall serve as our workflow.

Referencing
===========

There will be catalogued pre-defined rehearsal mark `.ly` files that correspond
with the range of measures associated with that mark. The work begins at 0,
which means that file associated with `~0.ly` will be referencing the beginning
of the piece till the end of the measure preceding 1. `~1.ly` will begin
starting with the measure marked with “1” and continue until the measure
directly preceding “2” and so on.

Names
-----

The task of engraving the solo part will be separate than that of the orchestra
reduction. For this reason, the prefixes `solo` and `orch` will precede each
file in the repository to denote which part is being worked on.

Special cases
-------------

I am still deciding on whether or not to include the ossias. Overall, the pose a
challenge to the overall layout, and most recordings I have listened to do not
resort to these (with a great exception to the mov. 1 cadenzas). Thus, for now,
The ossias will be excluded until further notice.

For the mov. 1 cadenzas, they will be marked `cadenzaA.ly` and `cadenzaB.ly`.
Rachmaninoff wrote originally the “optional cadenza” as the original cadenza for
the concerto. He later decided, before it’s premier, that it was too fulfilling,
and decided to write a far more sprite cadenza, which is considered the
“standard.” `cadenzaA.ly` refers to the final published version of the cadenza
(but not his first) and `cadenzaB.ly` refers to the first cadenza he wrote, that
which was created as an option in the final publication.

\\include command
-----------------

To remove any headaches, I will setup a set of “inclusions” to be made in the
scores for initial output. These will always need to be included in the score,
but in the final days of engraving they will slowly vanish to create a master
score that will include all the files.

Questions?
==========

See my ContactME page.
