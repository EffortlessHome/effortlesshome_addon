#============================#
#   EffortlessHome ADDON DOCKERFILE  #
#============================#

ARG BUILD_FROM
FROM ${BUILD_FROM}

# Labels for Home Assistant
ARG BUILD_ARCH
ARG BUILD_DATE
ARG BUILD_DESCRIPTION
ARG BUILD_NAME
ARG BUILD_REF
ARG BUILD_REPOSITORY
ARG BUILD_VERSION

LABEL \
    io.hass.name="${BUILD_NAME}" \
    io.hass.description="${BUILD_DESCRIPTION}" \
    io.hass.arch="${BUILD_ARCH}" \
    io.hass.type="addon" \
    io.hass.version=${BUILD_VERSION} \
    maintainer="effortlesshome (https://github.com/EffortlessHome)"

