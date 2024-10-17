ARG version=8
FROM almalinux:${version:-8}
ARG COURSE="DEVOPS"
ARG TRAINER="NNR"
ARG DURATION
ENV DURATION=${DURATION}

CMD ["sleep","100"]
RUN echo "version:${version},course:${COURSE},trainer:${TRAINER} duration:${DURATION}"
