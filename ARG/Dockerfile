ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="Devops" \
    TRAINER="Sk"   \
    VERSION="${VERSION}"
ENV COURSE=${COURSE}
 #so we can access arguments after from as argument and can be run inside containers
RUN echo "Trainer=${TRAINER} && Course=${COURSE}"
CMD ["sleep","100"]