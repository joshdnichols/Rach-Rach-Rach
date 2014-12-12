Rach-Rach-Rach
==============

This is a project to re-engrave the Rachmaninoff Piano Concerto Op. 30 using LilyPond.

# Purpose
The Purpose of this project is to re-engrave my absolute favorite piano concerto. This work is what led me to major in music in college, and I've a keen awareness of it's interpretation. I've listened to it countless hours and have practically memorized it.

# Plan
The plan is to go step by step through [this](http://petrucci.mus.auth.gr/imglnks/usimg/1/1c/IMSLP03554-Rachmaninov-Op30arr2p4h.pdf) arrangement of the 2 piano score. It will be worked on page by page, with exception to the cadenzas in the first movement. 
# Problem Solving
The first point of conflict that is most obvious with this work (or any work's of Rachmaninoff) is solving engraving problems with the score. This will be by far one of the most difficult works ever produced using LilyPond (although, LilyPond can handle it just fine). I recently engraved [this](http://petrucci.mus.auth.gr/imglnks/usimg/b/bc/IMSLP355543-PMLP02017-RachmaninoffOp23No10.pdf) piano prelude of his, and it was more challenging than I expected.

To do any problem solving it will usually involve some part of "tweaking" the source. There will be many questions about voicing, proper placement of slurs, etc. Fingerings will become an issue. The only way to do this is by trial and error.

# Known Issues
Tie Columns and their shape can be distorted. Fixing this has not yet come around in the LilyPond documentation.

# Recommendations and Requirements
I strongly suggest getting very acquanted with LilyPond's documentation, especially the Learning Manual and the Notation Reference. I would also setup a source file for your tweaks, because with works like this it will become necessary to revisit these tweaks.

I require the use of [frescobaldi](http://frescobaldi.org/). It saves a lot of headache and needless syntax searching in the documentation (with usage of autocomplete). It is available on all platforms.

I strongly suggest using the stable version of LilyPond. I also require the use of [openlilylib-fonts](http://fonts.openlilylib.org). You must change the `font.scm` and update it using the very easy and straightforward instructions provided on the website. You must also install the alternative fonts mentioned there. They are all free.

In the final analysis, we will use a modified score setup that will not use all the same glyphs as emmentaler.

# Other Requirements
I will soon upload a `include-me.ily` file that will help curtail many of the initial engraving challenges with this work. I will also upload an optional `opt-style-sheet.ly` that will further remove any need to manually override some of the markup spaces in headers, paragraphs, etc.

# Future Changes
My philosophy may change drastically with regard to the "how" and "how fast," but not so much methodology and structure. I will also not deviate from the official documentation's approach to engraving.

# PostScript
I will say that most of the engraving found in the Op. 23, No. 10 example listed above was standard engraving. LilyPond's ability to perform out-of-the-box is outstanding. This is why I chose it for this project; I would have spent twice as much time tweaking with with other engraving applications.
