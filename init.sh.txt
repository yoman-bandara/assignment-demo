#!/bin/bash

current_timezone=EST

curl "http://worldtimeapi.org/api/timezone/{$current_timezone}" > /home/ubuntu/nginx/output.json

