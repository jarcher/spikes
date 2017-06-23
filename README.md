# Spikes
Many organizations are trying to automate their efforts to migrate to container technology. Part of that effort is to identify where effort is needed in order to lift-and-shift .Net applications to containers.  Spikes is a Ansible based utility that executes APIPort agaginst a .Net project and then if it passes with 100% portability to the targeted supported CLR runtime will use the s2i builder script to automate the image creation that can be deployed to Openshift.


