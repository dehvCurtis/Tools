# Retire.js

## Example

`cd` to directory with Dockerfile

`docker build . -t=retire`

confirm container

`docker run --rm -v $PWD:/app retire -v`

download vulnerable jquery

`wget https://code.jquery.com/jquery-1.4.min.js`

run rest against vulnerable jquery

`docker run --rm -v $PWD:/app retire -v`