slim-complete-set
==========

This is a simple repository with ONLY submodules, including all slim-based packages as released on Github on account moliad.

The purpose of this repo is to make it a simple one stop single entry point to get all my libaries in a single place, pre-organised as other project repositories would expect them.

This repository is also included in other project which just need a quick link to all links to keep it simple.

Beware
------

Being built using the standard Git Submodule system you must be careful when manipulating the sub modules directly.  aAny updates to the master repository may reset the submodules files, including your changs and even delete your new files.

An example of this is if you switch branches, it will reset all submodules and then restore them as they where setup when the parent repository was when the branch was comitted.  if one of the submodules doesn't have the branch as part of its data, the submodule may be completely removed from the repository.

For this reason, one should only use the libs-complete-set repository as a way to be up to date on official releases.  If you wish to fix and contribute to modules, you should clone the library package repo directly and tweak it from there.

Furthermore, you may easily replicate this repository on your own, its basically just a root dir with all library packages added.  This will allow you to version and update each library package and file independently.

