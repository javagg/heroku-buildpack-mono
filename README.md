heroku-buildpack-mono
=====================
This is a Heroku buildpack for Mono that will run ASP.NET and Katana/OWIN applications.

It uses Mono 3.4.0.

## Usage

Example usage:

    $ heroku create --buildpack http://github.com/friism/heroku-buildpack-mono.git
    $ git push heroku master
