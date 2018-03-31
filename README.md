# Picture Structure

This repository configures the Docker containers required to run a local
instance of [Picture](https://pi.ctu.re).

See the main [GitHub repository of Picture](https://github.com/vinc/pi.ctu.re)
for more information.

## Usage

    $ git clone --recursive https://github.com/vinc/stru.ctu.re
    $ docker-compose up
    $ docker-compose exec web rails db:setup
    $ docker-compose exec web rails generate admin
