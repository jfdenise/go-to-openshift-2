LABEL org.wildfly.glow.feature-packs=wildfly-galleon-pack_32.0.1.Final,wildfly-cloud-galleon-pack_7.0.0.Final
LABEL org.wildfly.glow.layers=ee-core-profile-server,jpa,ejb-lite,jaxrs,jsf,h2-driver
FROM quay.io/wildfly/wildfly-runtime:latest
COPY server $JBOSS_HOME
USER root
RUN chown -R jboss:root $JBOSS_HOME && chmod -R ug+rwX $JBOSS_HOME
USER jboss