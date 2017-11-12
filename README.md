# A post-processor for user-wide compile database

This prunes duplicate entries in the database and generates similar entries for
header files, since some tools want to work on that too but they are not
compiled during normal build.
