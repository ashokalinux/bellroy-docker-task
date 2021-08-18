# bellroy-docker-task
DevOps Engineer application task

Thanks for applying for a position at Bellroy! You're here because the position requires some DevOps skills. This exercise has been designed to test your basic Docker familiarity.

This is designed to be a relatively quick task even if you're not completely familiar with the technologies involved. If this takes you longer than an hour or two to complete, you might reconsider applying for this role.
The brief

The data team have decided that they think they'd like to use shinyproxy to share their data analysis results with the rest of the company; they need a hand in setting things up.

You need to write a Dockerfile that:

    runs on Ubuntu 20.04 to keep it consistent with other environments
    installs R 3.6.3 from a trusted source
    make sure the locale is set to en_US.utf8
    installs the R packages: shiny, rmarkdown and any OS packages they may need to build
    adds the Rprofile.site file to /usr/lib/R/etc/ on the docker image
    Grabs the demo package from here and installs it
    Runs the shinyproxy::run_01_hello() R script

Send your application through Greenhouse along with any other artefacts the Dockerfile requires to assemble an image (note that you'll need to set the file format to TXT in order to attach them directly to your Greenhouse application).

If you have any issues submitting your application, please [email careers@bellroy.com](mailto:careers@bellroy.com].
