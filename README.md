# assignment-1
assignment
Purva@LAPTOP-48VFS045 MINGW64 ~
$ cd desktop

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop
$ mkdir shopping

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop
$ git init shopping
Initialized empty Git repository in C:/Users/Purva/Desktop/shopping/.git/

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop
$ cd shopping

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ touch yard.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ touch groceries.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git add .

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git commit -m 'create yard and groceries lists'
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Purva@LAPTOP-48VFS045.(none)')

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git config -- user.email "purvamp1905@gmail.com"

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git config -- user.name "purva"

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git commit -m 'create yard and groceries lists'
[master (root-commit) 117a902] create yard and groceries lists
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 groceries.txt
 create mode 100644 yard.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git add groceries.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git commit -m 'add ingredients for tomato soup'
[master 90c8e01] add ingredients for tomato soup
 1 file changed, 3 insertions(+)

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git add yard.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git commit -m 'add items needed for garden box'
[master 653c633] add items needed for garden box
 1 file changed, 2 insertions(+)

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git add .

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git commit -m 'add items needed to grow potatoes'
[master 98cf211] add items needed to grow potatoes
 2 files changed, 2 insertions(+), 1 deletion(-)

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$ git log
commit 98cf2113efe67659049e044c558056405b093538 (HEAD -> master)
Author: purva <purvamp1905@gmail.com>
Date:   Mon Mar 6 15:39:27 2023 +0530

    add items needed to grow potatoes

commit 653c6337858b176ddf4f45ce78492a270027f24e
Author: purva <purvamp1905@gmail.com>
Date:   Mon Mar 6 13:53:11 2023 +0530

    add items needed for garden box

commit 90c8e0194b88a79352eb91222e7ee4d92bb4e9f6
Author: purva <purvamp1905@gmail.com>
Date:   Mon Mar 6 13:51:46 2023 +0530

    add ingredients for tomato soup

commit 117a9024f885b2fcd5f9e6be47d631ccd015d5df
Author: purva <purvamp1905@gmail.com>
Date:   Mon Mar 6 13:48:01 2023 +0530

    create yard and groceries lists

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/shopping (master)
$
