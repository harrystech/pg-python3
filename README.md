# pg-python3
Base image for python3 applications that use postgres and may want to bootstrap with bash &amp; git


Normal use case would be to import this image and COPY a bootstrap.sh script that git clones and installs your application, or use this image in CI (for instance, Circle 2) for your application