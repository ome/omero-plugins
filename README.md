OMERO plugins
=============

This collection of OMERO plugins allows us to maintain a single cron job
which runs dependabot daily for all the listed repositories (instead of
maintaining separate cron jobs for each one). 

Running the bot daily for each repository allows us to check that they
are passing with the latest dependencies, including the latest OMERO release,
even when there are no changes and no PRs open for each repo itself.

This list of plugins points to the tip of the master branch for each
plugin and the link is bumped automatically when new PRs are merged.

The list is also used by the daily merge job at https://merge-ci.openmicroscopy.org/jenkins/job/OMERO-plugins-push/ to iterate through each repository,
merge any open PRs and push the merged branch to repos owned by
https://github.com/snoopycrimecop.
