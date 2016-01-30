# Well-then: Unofficial builds for the kool kidz.

Eli Bradley offers patches to [@larry0618](https://github.com/larry0618/)'s cutting edge GitHub repository design template, "Well-then", in the form of patch-n builds. You can see the data on all of my patch-n builds in the table below. If you would like stability in your Well-then builds, check back here to know most issues that plague Well-then, and overall what builds you should be using currently. However, these builds shouldn't belong in a production environment; there is no warranty. Thank you, and enjoy!

|| [initial](https://github.com/EtherTyper/Well-then/tree/initial) | [master](https://github.com/larry0618/Well-then/tree/master) | [patch-0](https://github.com/EtherTyper/Well-then/tree/patch-0) | [gh-pages](https://github.com/larry0618/Well-then/tree/gh-pages) | [patch-1](https://github.com/EtherTyper/Well-then/tree/patch-1) | [patch-2](https://github.com/EtherTyper/Well-then/tree/patch-2) | [patch-3](https://github.com/EtherTyper/Well-then/tree/patch-3) | [patch-4](https://github.com/EtherTyper/Well-then/tree/patch-4) |
|---|---|---|---|---|---|---|---|---|
| initial | equivalent | compatible | compatible | compatible | compatible | compatible | compatible | compatible |
| master | merged | equivalent | merged | incompatible | incompatible | incompatible | merged | compatible |
| patch-0 | merged | compatible | equivalent | compatible | compatible | compatible | compatible | compatible |
| gh-pages | merged | incompatible | merged | equivalent | incompatible | incompatible | merged | compatible |
| patch-1 | merged | incompatible | merged | incompatible | equivalent | incompatible | incompatible | incompatible |
| patch-2 | merged | incompatible | merged | incompatible | incompatible | equivalent | incompatible | incompatible |
| patch-3 | merged | compatible | merged | compatible | incompatible | incompatible | equivalent | compatible |
| patch-4 | merged | merged | merged | merged | incompatible | incompatible | merged | equivalent |
| issue | N/A | N/A | N/A | N/A | [#2](https://github.com/larry0618/Well-then/issues/2) | [#6](https://github.com/larry0618/Well-then/issues/6) | [#8](https://github.com/larry0618/Well-then/issues/8) | N/A |
| pull | N/A | N/A | [#1](https://github.com/larry0618/Well-then/pull/1) | N/A | [#3](https://github.com/larry0618/Well-then/pull/3) | [#5](https://github.com/larry0618/Well-then/pull/5) | [#7](https://github.com/larry0618/Well-then/pull/7) & [#9](https://github.com/larry0618/Well-then/pull/9) | N/A |
| reftype | tag | branch | release | branch | release | release | release | release |
###### Note: 'merged' means collumns have been merged into rows, and likewise, 'compatible' means collumns _may_ be merged into rows using fast-forward merge style. Question marks symbolize uncertainty, as the branches they concern do not belong in my project, and I'm not regularly in contact with the owner of the vanilla repository, [larry0618/Well-then](https://github.com/larry0618/Well-then/). Support for master and gh-pages builds belong there, not here.

Currently, larry0618/master and larry0618/gh-pages have different commit trees though almost equivalent working directories @ HEAD. The only major difference is that the master branch's title is now ```<title> "gh-pages"</title>``` while gh-pages still contains the title text ```<title> "WHY WOULD YOU LOOK UP HERE"</title>```. Another less important detail is that master left an empty \n where the "PARADOX" and the "Pixel Quest: The Lost Gifts" emulator used to be, unlike gh-pages. They are both ancestored by my stable patch-3 release tag, and are the parents of my final patch-4 release tag, which compiles all changes and formats index.html with tab delimitation. Thanks for visiting!
