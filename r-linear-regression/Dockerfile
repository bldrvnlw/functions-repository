FROM hbpmip/r-job:629ae86

MAINTAINER ludovic.claude54@gmail.com

RUN installGithub.r LREN-CHUV/hbplregress@c6700452

LABEL eu.humanbrainproject.function=linear-regression \
      eu.humanbrainproject.function.location=node \
      eu.humanbrainproject.function.version=0.1 \
      eu.humanbrainproject.function.author="Lester Melie-Garcia" \
      eu.humanbrainproject.function.organisation="LREN, CHUV" \
      eu.humanbrainproject.function.date="2015-06-27"

COPY main.R pfa.yml /src/
COPY tests/testthat.R /src/tests/
COPY tests/testthat/ /src/tests/testthat/