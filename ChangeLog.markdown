# 1.3.2 - 2010-03-11

  * Deal cleanly with any single quotes found in tag comments so that the 'git tag' commands run correctly

# 1.3.1 - 2009-06-09

  Thanks to iteman for finding a problem with the tagging process and providing a patch.
  
  * Fixed a problem with creating actual git tags when the SVN tags path was named anything other than 'tags.'

# 1.3.0 - 2009-06-09

  Many thanks to mss for the patches making up most of this release.

  * Fixed a problem where tags didn't get the original date and time.
  * New switch --exclude which can be used to specify a PCRE pattern to exclude paths from the import.
  * New switches --no{trunk,branches,tags} to skip import of those.
  * Improved docs.

# 1.2.4 - 2009-05-04

  * No changes.  I ran the jeweler command twice inadvertently.  Tearing down the release would be more harmful than helpful.

# 1.2.3 - 2009-05-04

  * Yanked out the code referencing the gem by name.  This shouldn't be necessary at all.

# 1.2.2 - 2009-05-04

  * Updated the reference gem in the binary to use this one and not the one on RubyForge.

# 1.2.1 - 2009-04-19

  * Fixed a problem with the svn2git binary not loading command-line args properly.

# 1.2.0 - 2009-04-17

  * Reworked command-line options so they work similarly to every other app in the world.
  * Better error messaging when no URL provided.
  * Improved docs.

# 1.1.1 - 2009-04-15
  
  * Started using Jeweler for gem management.
  * Fixed issue with not loading up RubyGems appropriately.

# 1.1.0 - 2009-01-02

  * First release since nirvdrum fork.
  
  * Fixed issues with handling of tags and branches.
  * Added better logging of output from git-svn.
  * Wrap external command processing to capture failures.

# 1.0.0 - 2008-07-19

  * Forked version from jcoglan.
