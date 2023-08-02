# https://developers.home-assistant.io/docs/add-ons/configuration#add-on-dockerfile
ARG BUILD_FROM
FROM $BUILD_FROM

# Execute during the build of the image
ENTRYPOINT [ "/app/api" ]
CMD [ "/data/config.yml" ]