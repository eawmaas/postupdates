## Warning:
This module does not work plug-and-play, it's far from complete!
Several things have to be added and several changes to Chyrp Lite need to be done for this module to work and to produce valid HTMl5

## Notes:
-changes themes/topaz/feathers/compositions.twig
-momentarily changes themes/topaz/feathers/text.twig too
-needs changes in all feathers in all themes to be able to work

-the themes-files are until now the only two feathers that I changed, I have tried to do it by changing themes/topaz/content/post.twig but then you can only place it on top (above the title) which pushes everything down or between the post and the footer, but it has to be some sort of news-headline and that shoud be on top, preferrably above the updated text, which is inside the post-content.

## Future functionalities / to-do's:
I want to add at least two functionalities in the future that are related to this:
1.: Add a section "Last updated posts" to the sideline
2.: Add an option "Sort posts on last-updated" (instead of creation-date)
3.: Add an option to show a "New"-icon in front of "Post updated:" within a certain time-period from now, like "show new-icon on all posts updated the last 3 weeks (or whatever value you want)"

## Translations:
The text that has to be added to the feathers contains a translatable string. Inside the .pot-file you have to specify which files contain the text, as for now that can only be two feathers in one theme (topaz) and it should be for all feathers in all themes

## More
Will come (some day)

## Documentation

The Chyrp Lite [wiki](https://chyrplite.net/wiki/) has comprehensive documentation
for users and developers.

## Authors

Chyrp Lite was created by the following people:

* Lite Developer: Daniel Pimley
* Chyrp Developer: Arian Xhezairi
* Project Founder: Alex Suraci
* Module authors and other contributors.

## Licenses

Chyrp Lite is Copyright 2008-2023 Alex Suraci, Arian Xhezairi, Daniel Pimley, and other contributors,
distributed under the [BSD license](https://raw.githubusercontent.com/xenocrat/chyrp-lite/master/LICENSE.md).
Please see the [licenses](licenses) directory for the full license text of all software packages distributed with Chyrp Lite.
