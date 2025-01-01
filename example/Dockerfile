# https://developers.home-assistant.io/docs/add-ons/configuration#add-on-dockerfile
ARG BUILD_FROM
FROM $BUILD_FROM

ARG AUTO_INCREMENT_ASSET_ID
FROM $AUTO-INCREMENT-ASSET-ID

ENV HBOX_OPTIONS_AUTO_INCREMENT_ASSET_ID=$AUTO-INCREMENT-ASSET-ID

LABEL org.opencontainers.image.source=https://github.com/sysadminsmedia/homebox-ha-addon
#comment
# Execute during the build of the image
ENTRYPOINT [ "/app/api" ]
CMD [ "/data/config.yml" ]
