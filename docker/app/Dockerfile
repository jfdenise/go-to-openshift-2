FROM quay.io/jdenise/pipeline-wildfly-server:23ff1527dad0be3cea3868c8a907fbb7
COPY --chown=jboss:root deployments/* $JBOSS_HOME/standalone/deployments
RUN chmod -R ug+rwX $JBOSS_HOME
