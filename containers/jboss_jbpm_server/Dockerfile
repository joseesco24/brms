# ---------------------------------------------------------------------------------------------------------------------
# ** info: stage 1: building stage
# ---------------------------------------------------------------------------------------------------------------------

# ---------------------------------------------------------------------------------------------------------------------
# ** stage 2: production image
# ---------------------------------------------------------------------------------------------------------------------

# ** info: declaration of the production image base version
FROM quay.io/kiegroup/jbpm-server-full:7.74.0.Final

# ** info: declaration of the configuration directory
ARG APP_CONFIGURATION_DIRECTORY=/opt/jboss/wildfly/standalone/configuration

# ** info: declaration of the projects directory
# ARG APP_PROJECTS_DIRECTORY=/opt/jboss/wildfly/bin/.niogit

# ** info: copying the configuration files from the building context to the configuration directory
COPY ["configuration" ,"$APP_CONFIGURATION_DIRECTORY/"]

# ** info: copying the projects files from the building context to the projects directory
# COPY ["projects" ,"$APP_PROJECTS_DIRECTORY/"]