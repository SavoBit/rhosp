FROM registry.access.redhat.com/rhosp13/openstack-heat-engine:13.0-63
LABEL vendor="Avi" name="avi-rhosp13/openstack-heat-engine" version="13.0-63-avi-17.2"

USER root
RUN rpm -ivh https://github.com/avinetworks/avi-heat/releases/download/v17.2.7/aviheat-17.2.7b201812211855-1.noarch.rpm

USER heat
