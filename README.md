# Rails Hello OpenAPI

A quick "Hello World" but for generating OpenAPI, using the Ruby on Rails extension [RSwag](https://github.com/rswag/rswag/).

This repository was built as sample code for the Bump.sh guide on [Generating OpenAPI docs for Ruby on Rails with RSwag](https://docs.bump.sh/guides/openapi/code-first-rails/).

## Usage

Clone the repository down to give it a try.

```
# Set everything up
$ bundle install

# Export the OpenAPI
$ rake rswag

# Take a look at the generated OpenAPI
cat swagger/api/swagger.yaml
```

Preview the API reference docs [on Bump.sh](https://bump.sh/bump-examples/hub/code-samples/doc/rails-hello-openapi).

## License

The contents of this repository are licensed under [CC BY-SA
  4.0](./LICENSE_CC-BY-SA-4.0).
