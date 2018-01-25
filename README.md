OpenShift test case.

This is a one single php file with echo hello world.


Steps:-
$ oc project test

$ oc process -f temp.json -v IMAGENUMBER=java | oc apply -f -
