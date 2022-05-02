## Hash
Jā, git uzskata, ka tie ir citi faili, jo pievienoti ar citu commit comandu un lidz ar to tiem git datubaze ir izveidojies jauns hash index.

## Teraform
Izmaiņas var apskatīies ar GitHub Desktop sadaļa History un no komandrindas >> git log

## Laura

$ git log --author Laura
- 78f90a64b E Fri Apr 29 11:58:1.. Laura Pacilio    Merge pull request #30956 from tigerblue77/patch-1
- e68ad5ec4 N Wed Apr 20 18:57:5.. Laura Pacilio    more edits origin/update-TF-WORKSPACE-variable
- 912e6ff6d N Wed Apr 20 18:54:5.. Laura Pacilio    Apply suggestions from PR review
    Update apt.mdx
    
## Laura Septembris
Nav veikusi commit
 - $ git log --after "2021-09-01" --before "2021-10-01"
- 618e9cf8e N Thu Sep 30.. James Bardin     test for unexpected data reads
- 016463ea9 N Tue Sep 28.. James Bardin     don't check all ancestors for data depends_on
- fe671206c N Wed Sep 29.. James Bardin     Add detail about the protocol deprecation
- 0062e7112 E Wed Sep 29.. Melissa Gurney ..Update publish.html.md (#29671)
- c9a5fdb36 E Wed Sep 29.. Zach Whaley      cliconfig: Fix error message about invalid credentials helper type
- f93f16824 E Wed Sep 29.. James Bardin     Merge pull request #29665 from hashicorp/jbardin/required_version
- ab0322e40 N Tue Sep 28.. James Bardin     remove debugging println
- c2e0d265c N Tue Sep 28.. James Bardin     LoadModule now always returns the module
- a53faf43f N Tue Sep 28.. James Bardin     return partial config from LoadConfig with errors
- 625e76867 N Tue Sep 28.. James Bardin     make sure required_version is checked before diags
- f60d55d6a N Mon Sep 27.. Martin Atkins    core: Emit only one warning for move collisions in destroy-plan mode
- 372814e49 E Mon Sep 27.. James Bardin     Merge pull request #29659 from hashicorp/jbardin/really-nested-within
- cac1f5c26 N Fri Sep 24.. James Bardin     refactoring: exhaustive NestedWithin checks
- e09bad76f N Fri Sep 24.. Alisdair McDiar..build: Add exhaustive switch statement lint
- a742d7ee8 E Fri Sep 24.. Alisdair McDiar..Merge pull request #29649 from hashicorp/alisdair/json-ui-exhaustiveness
- b699391d0 N Fri Sep 24.. Alisdair McDiar..json-output: Add change reasons to explain deletes
- 8ce2254ad E Fri Sep 24.. James Bardin     Merge pull request #29647 from hashicorp/jbardin/test-temp-cleanup
- 9847eaa9c N Fri Sep 24.. James Bardin     remove usage of MinItems/MaxItems
- 24a2bd630 N Tue Sep 14.. James Bardin     tfproto version 6.1
- c8cd0b1e7 E Fri Sep 24.. James Bardin     Merge pull request #29624 from hashicorp/jbardin/no-block-to-attr
- 50fac6afd E Fri Sep 24.. Alisdair McDiar..Merge pull request #29645 from hashicorp/alisdair/verify-remote-terraform-version-update
- 57318ef56 N Fri Sep 24.. Alisdair McDiar..backend/remote: Support interop from 0.14 to 1.1
- f1e9d88dd E Fri Sep 24.. Alisdair McDiar..Merge pull request #29640 from hashicorp/alisdair/fix-refresh-only-with-orphans
- 5d620303e E Thu Sep 23.. Martin Atkins    Update CHANGELOG.md
- 0f76e3a4e E Thu Sep 23.. Martin Atkins    Update CHANGELOG.md
- d97ef10bb N Thu Sep 23.. Martin Atkins    core: Don't return other errors if move statements are invalid
- 1bff623fd N Thu Sep 23.. Martin Atkins    core: Report a warning if any moves get blocked
- 04f9e7148 N Wed Sep 22.. Martin Atkins    command/format: Include deletion reasons in plan report
- a1a713cf2 N Wed Sep 22.. Martin Atkins    core: Report ActionReasons when we plan to delete "orphans"
- 7b99861b1 N Wed Sep 22.. Martin Atkins    refactoring: Don't implicitly move for resources with for_each
- 9c078c27c N Tue Sep 14.. James Bardin     temp path clean for some backend tests
- ceb580ec4 N Thu Sep 23.. Alisdair McDiar..core: Fix refresh-only interaction with orphans
- db6ca866f E Thu Sep 23.. Chris Arcand     Merge pull request #29627 from hashicorp/auto-select-single-workspace
- 171cdbbf9 N Wed Sep 22.. Chris Arcand     command: Clean up testInputResponseMap before failing on unused answers
- 60bc7aa05 N Tue Sep 21.. Chris Arcand     command: Auto-select single workspace if necessary
- 8706a18c4 N Wed Sep 22.. James Bardin     refine the skipFixup heuristic
- cd1d30ea9 N Wed Sep 22.. hc-github-team-..Cleanup after v1.1.0-alpha20210922 release
- d14bbbb6f E Wed Sep 22.. hc-github-team-..Release v1.1.0-alpha20210922 tag: v1.1.0-alpha20210922
- 3f1c15c79 E Wed Sep 22.. Martin Atkins    Upgrade to Go 1.17.1
- 6b4e73af4 N Wed Sep 22.. James Bardin     skip the blocktoattr fixup with nested types
- 83f037667 N Tue Sep 21.. Martin Atkins    refactoring: ApplyMoves new return type


## *

Katram commit ir divi datumi,  - AuthorDate and CommitDate

- $ git log --after "2021-04-20" --before "2021-04-21" --pretty=fuller
- commit f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea
- Author:     James Bardin <j.bardin@gmail.com>
- AuthorDate: Fri Apr 16 17:11:27 2021 -0400
- Commit:     James Bardin <j.bardin@gmail.com>
- CommitDate: Tue Apr 20 17:04:56 2021 -0400



