# ===========================================
# This is the docker file for task 6
# ===========================================

# Using nginx, the latest version of course.
FROM nginx:latest

# Copy FROM DIRECRTORY __ TO DIRECTORY.
# I'm 99% sure you can use . in place of the full
# Directory, but this will also work.
COPY softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy the configuration file as well.
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
