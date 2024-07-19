FROM quay.io/jdenise/pipeline-wildfly-server:069369af0b2192b90e874e2eee93abcc
COPY --chown=jboss:root deployments/* $JBOSS_HOME/standalone/deployments
RUN chmod -R ug+rwX $JBOSS_HOME
