FROM mongo:7.0
# copying the .js files to the initdb folder for catalogue to be effective
COPY *.js /docker-entrypoint-initdb.d
# in every database we will be having this kind of initdb.d dir or folder
# this allow the user to add and define our db start scripts to set up our databases when container starts