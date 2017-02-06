# docker-patchwork

Docker image for [patchwork](https://ssbc.github.io/patchwork/). Tested on Linux only.

## Usage

Start the daemon:

    docker run -d --rm -p 7777:7777 --net=host -v ~/.ssb:/home/node/.ssb --name patchwork mazzolino/patchwork

Then, open the browser at [http://localhost:7777](http://localhost:7777).
