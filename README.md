Red Hat JBoss Business Resource Planner Workshop
================================================
This git repository helps you get up and running quickly with a 
Cloud hosted workshop getting you started with complex planning 
of resources.

Enjoy!

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a PHP application

    rhc app create plannerworkshop -t php-5.4 --from-code git://github.com/eschabell/openshift-planner-workshop.git

That's it, you can now start your workshop at:

    http://plannerworkshop-$your_domain.rhcloud.com

![Planner Workshop](https://raw.githubusercontent.com/eschabell/openshift-planner-workshop/master/php/cover.png)

