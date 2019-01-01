# sonarqube-on-openshift
This project helps you to deploy Sonar Qube with integration with postgress on Openshift.

Deployment on OPenshift is straightforward.
>oc new-app -f  sonarqube-postgresql-template.yaml --param=SONARQUBE_VERSION=7.5

Refer the below blog for more details
https://arjunsreepad.com/2018/12/19/hosting-sonar-qube-on-open-shift/

