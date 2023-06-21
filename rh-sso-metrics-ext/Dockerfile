 FROM registry.redhat.io/rh-sso-7/sso74-openshift-rhel8:latest
      ARG aerogear_version=2.5.0
      RUN cd /opt/eap/standalone/deployments && \
      curl -LO https://github.com/aerogear/keycloak-metrics-spi/releases/download/${aerogear_version}/keycloak-metrics-spi-${aerogear_version}.jar && \
      touch keycloak-metrics-spi-${aerogear_version}.jar.dodeploy && \
      cd -
      
