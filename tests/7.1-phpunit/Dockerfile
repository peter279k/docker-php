FROM phpearth/test:7.1-cli

RUN set -x \
    && apk add --no-cache composer \
    && composer global require phpunit/phpunit

ENV PATH /root/.composer/vendor/bin:$PATH
