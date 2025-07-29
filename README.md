# bluu_daily-event-reporting-tool

A little tool that I made during my Summer 2025 internship at Bluu, Inc.

All names and projects have been redacted, but the original functionality remains.

## FAQ

### Why a single file?

I didn't have a way to transpile/compile into the final webpage, so I ended up
just writing a giant monolithic file. It was not as painful as I thought it would
be, probably because I kept the scope quite small.

Commit history is a bit weird because I didn't have `git` on my work computer.
Dates of when I worked on each revision were pulled from the metadata of the versioned
files of the page that I kept.

### Why have two methods of importing?

Initially I wanted to use the clipboard because it's easy to copy-paste. However,
browsers keep nagging you about pages accessing the clipboard and there is (to
my knowledge) no way to have browsers persistently remember that it's okay to
give permanent clipboard access to local webpages.

Therefore the drag-and-drop-files method was added and I was surprised it worked
this well. The code for implementing the feature wasn't that complicated, either.

### Future plans?

Perhaps I would modularize and migrate this to a Vite project when my internship
is over, but I plan to have a `final-revision` tag for the last-ever revision of
the initial monolithic file that I created once my internship wraps up. And
the project will then be archived, as-is.