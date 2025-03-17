FROM almalinux:9
RUN dnf install nginx -y
LABEL environment="dev"\
      project="expense"\
      learner="madhukar"
CMD ["nginx","-g","daemon off;"]
