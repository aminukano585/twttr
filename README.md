# Twttr App &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/aminukano585/twttr/blob/master/LICENSE.md) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md) [![Custom Rails Badge](https://img.shields.io/badge/dynamic/json.svg?style=flat&logo=rails&logoColor=%23cc0000&label=Ruby%20on%20Rails&url=https://raw.githubusercontent.com/aminukano585/twttr/master/package.json&query=$.rails&color=brightgreen)](https://github.com/rails/rails/tree/v6.0.2.1)

A simple twttr app, you can view the live site <a href="https://safe-beyond-09622.herokuapp.com/" target="_blank">here<a>

## Getting Started

To get started with the app, clone the repo and then install the needed gems:

```
$ yarn add jquery@3.4.1 bootstrap@3.4.1
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails db:seed
$ rails server
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/aminukano585/twttr. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

This project is available as open source under the terms of the [MIT License](https://github.com/aminukano585/twttr/blob/master/LICENSE.md).

## Code of Conduct

Everyone interacting in this project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/aminukano585/twttr/blob/master/CODE_OF_CONDUCT.md).

## Deployment

Coming sooner...