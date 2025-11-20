ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="Devops" \
    TRAINER="Sk"   \
    VERSION="${VERSION}"
ENV COURSE=${COURSE}
RUN echo "Trainer=${TRAINER} && Course=${COURSE}"
CMD ["sleep","100"]