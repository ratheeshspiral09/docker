#!/bin/bash
docker build -t samplephp .
docker run -d -p 8010:80 samplephp /usr/sbin/apache2ctl -D FOREGROUND
sensible-browser http://localhost:8010/phpinfo.php
