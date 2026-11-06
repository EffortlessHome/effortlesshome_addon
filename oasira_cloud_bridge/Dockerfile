#============================#
#   ADDON DOCKERFILE  #
#============================#
# This Dockerfile is not used when build.json is present
# Home Assistant pulls pre-built images from Docker Hub via build.json
<<<<<<< HEAD:effortlesshome_cloud_bridge/Dockerfile
# The actual images are built separately and pushed to effortlesshome/effortlesshomecloudbridge
=======
# The actual images are built separately and pushed to EffortlessHome/effortlesshomecloudbridge
>>>>>>> 0b3348a11cddc05c9484a3dbfa2ffd51254950f4:effortlesshome_cloud_bridge/Dockerfile

ARG BUILD_FROM
FROM ${BUILD_FROM}

# This is a placeholder Dockerfile required by Home Assistant
# The actual addon uses pre-built images specified in build.json:
# - EffortlessHome/EffortlessHomecloudbridge:latest-amd64
# - EffortlessHome/EffortlessHomecloudbridge:latest-aarch64

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
<<<<<<< HEAD:effortlesshome_cloud_bridge/Dockerfile
    maintainer="EffortlessHome (https://github.com/EffortlessHome)"
=======
    maintainer="EffortlessHome (https://github.com/EffortlessHome)"
>>>>>>> 0b3348a11cddc05c9484a3dbfa2ffd51254950f4:effortlesshome_cloud_bridge/Dockerfile
