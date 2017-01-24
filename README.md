# Spotty
A very social spot guide.
This is a Rails 5 API application. Its built to work in conjunction with
a front-end Javascript SPA.

## Authentication
This app is built on stateless authentication with JWT.
There is no session middleware.

## Requirements
- Postgres 9.5+
- Ruby 2.3.1

## Documentation
API documentation is available at http://www.rubydoc.info/github/maxcal/spotty/master.
This project is documented with [YARD](http://yardoc.org/).

You are encouraged to write documentation for all public methods.
You can run a live version of the docs server with:
```SH
  yard server -s webrick --reload
```

## Testing
This app embraces Behavior Driven development. Specs are written in
RSpec.

This app uses FactoryGirl instead of fixtures.

Guidelines
- Test public methods.
- Use request specs instead of controller specs.
