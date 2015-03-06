# beanstalk_deploy

Usage:
    /usr/local/sbin/beanstalk_deploy -revision <REVISION> -branch <BRANCH> [OPTION]

Description:
    Checkout portal website code from git and place in <PATH>

Required arguments:
   -r, --revision        Git revision hash
   -b, --branch          Current git branch that is being deployed.

Optional arguments:
   -p, --path            Path to the document root, default is /var/www/portal.csuglobal.edu
   --debug               Print debugging information
   --dryrun              Don't actually do anything, just pretend to
   --from_scratch        This will be a 1 or 0 depending on whether the deployment is from scratch or not.
   --help                Print this help page
   --quiet               Shut up already!
   --rollback            This will be a 1 or 0 whether deployment is a rollback or not.
   --auto                Substitutes 1 or 0 whether deployment was triggered automatically or manually.
   --comment             Current deployment comment.
   --verbose             Be more talkative, absolutely garrulous
   --release_id          Unique ID for the triggered deployment.
   --remote_path         Remote path from settings in a particular deployment server.
   --timestamp_utc       Time when deployment was triggered in UNIX epoch format.
   --user_name           Name of the user who triggered the deployment.
   --user_email          Email address of the user who triggered the deployment.

