# Make the Java base image and version configurable (useful for trying newer Java versions and flavors)
ARG BASE_IMAGE="poikilotherm/testbase:unstable"
FROM $BASE_IMAGE

# Copy app and deps from assembly in proper layers
COPY maven/deps /app/WEB-INF/lib
COPY maven/app /app
