# Instawall

**Ariadne Cookbook**

This cookbook is intended to perform the "last mile" of configuration
needed to bring the Ariadne environment to a fully provisioned state
for development of this install profile:

 * https://bitbucket.org/blinkreaction/instawall

# Quick Setup

If you already have an Ariadne environment configured and set up on your
system, you may run the following commands to install this project
cookbook and boot Ariadne:

    cd path/to/ariadne
    rake "init_project[https://github.com/posulliv/ariadne-instawall]"
    project=instawall branch=master vagrant up

When the Chef run has completed, your local site with have a
username/password pair of `admin`/`S4mpleP^ssword`, and will be
available at:

    http://instawall.dev

Full instructions for project setup are available in the [Ariadne's
official README][ariadne-project-setup].


