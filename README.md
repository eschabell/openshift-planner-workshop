Red Hat JBoss Business Resource Planner Workshop
================================================
This git repository helps you get up and running quickly with a 
cloud hosted workshop on JBoss Business Resource Planner component
found in JBoss BPM Suite and JBoss BRMS products.

Install with one click
----------------------
[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to  install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=php-5.4&initial_git_url=https://github.com/eschabell/openshift-planner-workshop.git&name=plannerworkshop)

Manual setup on OpenShift
-------------------------

Create a PHP application

    rhc app create plannerworkshop -t php-5.4 --from-code git://github.com/eschabell/openshift-planner-workshop.git

That's it, you can now start your workshop at:

    http://plannerworkshop-$your_domain.rhcloud.com

![Planner Workshop](https://raw.githubusercontent.com/eschabell/openshift-planner-workshop/master/php/cover.png)

