Homebrew-alt
============
This repository contains "unofficial" formulae for [Homebrew](https://github.com/mxcl/homebrew).

ATTN: the `duplicates`, `versions` and `unmaintained` directories have been moved to their own repositories:

 * [homebrew-dupes][]
 * [homebrew-versions][]
 * [homebrew-boneyard][]

Installing Homebrew-alt Formulae
--------------------------------
Just `brew tap adamv/alt` and then `brew install <formula>`.

If the formula conflicts with one in mxcl/master, you can `brew install adamv/alt/<formula>`.

You can also install via URL:

```
brew install https://raw.github.com/adamv/homebrew-alt/master/<directory>/<formula>.rb
```

Categories
----------
  * **fonts**  

  * **head-only**  
  Formulae that provide only the latest development HEAD.

  * **mono**  

  * **non-free**  
  Formulae that provide non-free software.

  * **other**  
  Miscellaneous formulae that do not meet the criteria for acceptance into mxcl/master.

Docs
----
`brew help`, `man brew`, or the Homebrew [wiki][].

[wiki]:http://wiki.github.com/mxcl/homebrew
[homebrew-dupes]:https://github.com/Homebrew/homebrew-dupes
[homebrew-versions]:https://github.com/Homebrew/homebrew-versions
[homebrew-boneyard]:https://github.com/Homebrew/homebrew-boneyard
