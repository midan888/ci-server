FROM jetbrains/teamcity-minimal-agent

RUN apt-get update -y && apt-get install apt-utils -y
RUN curl -sL https://deb.nodesource.com/setup_8.x | bash - \
    && apt-get install -y nodejs
