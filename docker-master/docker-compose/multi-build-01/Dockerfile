FROM drupal:latest

RUN apt-get update -y && apt-get install git -y \
      && rm -rf /var/lib/apt/lists/*

WORKDIR /var/www/html/themes

RUN git clone --branch 8.x-3.x --single-branch --depth 1 https://git.drupal.org/project/bootstrap.git

WORKDIR /var/www/html
