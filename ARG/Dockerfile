ARG version
FROM almalinux:${version:-9}
ARG course="DevOps with AWS" \
    duration= "120HRS"
ENV duration=$duration
RUN echo "Course: $course , Duration: $duration , version: $version"
CMD ["sleep", "100"]
