# Diary

I want to start keeping a diary, and this is a fun way to do it. It should keep adding more interesting stuff to this repo, and it also adds an interesting new feature to possibly add to the `md-wiki` project. However I name individual files (likely just the date formatting), I may want to add aliases to them for the purposes of automatic linking. There are a number of ways this could go:

* Adding links based on file contents. IE, if I mention Yosemite National Park somewhere in another file, it could note that it is also in this file.
    * Issue: this could lead to recursive linking between files and be confusing if there are more than two files with the relevant string
* Adding an `aliases.txt` file, or a master file combining this with `ignore.txt` and `description.txt` to describe what aliases files should go by
* Add a built in feature for parsing dates and allowing other date formats. (probably the most difficult, but rewarding, method).git 