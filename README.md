Release Dashboard
======================

A dashboard and utilities to track, display, and communicate release status.

Display a list of releases with deployment status.

Get a list of apps installed on each appserver with timestamp and version info (if available)

Show the release pipeline and stages for a release
 * release branch cut
 * release build number and status

For each product: 
 * will this app be included in the release (manual decision -- usually by PM)
 * what artifacts (app name, commit, build number) to release
 * which tasks are completed for this release
 * features to be verified
 * developer tests passing
 * **dev gateway**
 * promotion tests passing
 * deployed to test environment
 * features verified
 * regression tested
 * any open defects or unresolved issues
 * is this app ready to be released (manual decision -- usually by QE)
 * **qe gateway**
 * when is deployed scheduled
 * which artifiacts are to deployed
 * is the environment ok for deployment (manual decision -- usually by OPS) 
 * pre-deployment tasks completed
 * **deployment gateway**
 * deploy
 * smoketest
 * user acceptance
 * OPS status
 * **rollback gateway**

For each environment:
 * what products are deployed
 * what artifacts are deployed on each appserver
