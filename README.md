# Use this at your own peril

This is a handful of patches I collected from various support tickets to fix builds on my PowerPC based 10.4 Tiger system.  To wit:

1. m4: https://trac.macports.org/ticket/72527 -- credit to @hart-NTP
2. python313: https://trac.macports.org/ticket/71206?cversion=1&cnum_hist=19 -- credit to @glebm
3. m4: https://trac.macports.org/ticket/72527 -- credit to @hart-NTP
4. gawk: https://cgit.git.savannah.gnu.org/cgit/gawk.git/commit/?id=74d14530fc17d4e87b1f30b71049bb38eae76066 -- credit to Arnold Robbins


These popped up as they are in the prereq list for doing the local build of @classilla's fabulous TenFourFox project: https://github.com/classilla/tenfourfox?tab=readme-ov-file

Perhaps this is useful, perhaps not. 


## How to use this.
1. Clone this repo
2. Follow the instructions here to point macports to it: https://guide.macports.org/chunked/development.local-repositories.html
