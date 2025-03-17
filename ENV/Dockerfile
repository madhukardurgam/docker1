FROM almalinux:9
RUN dnf install nginx -y
ENV environment="dev"\
    project="expense"\
    learner="dmk"
CMD ["nginx","-g","daemon off;"]

