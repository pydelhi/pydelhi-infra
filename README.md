# pydelhi-infra

[![Build Status](https://travis-ci.org/pydelhi/pydelhi-infra.svg?branch=master)](https://travis-ci.org/pydelhi/pydelhi-infra)

Configurations of all the servers and applications hosted under pydelhi.org.

## Getting Started

Clone this repository to your local machine:

```shell
git clone --recursive git@github.com:pydelhi/pydelhi-infra.git
cd pydelhi-infra
```

Make sure you have [vagrant] and virtualbox installed, then run:

```shell
sudo pip install ansible
vagrant up
```

Login to the new machine with:

```shell
vagrant ssh
```

[vagrant]: https://www.vagrantup.com/downloads.html

## Contributing

- Search through existing open/closed github [issues].
- Open [new github issue] or send a pull-request,
- If that dosn't help, feel free to ask anything at [#pydelhi][pydelhi-irc] @ freenode.net

## Changelog

See: [CHANGELOG.md][changelog]

## Thanks

To all the [contributors].

[contributors]: ./CONTRIBUTORS.txt
[changelog]: CHANGELOG.md
[pydelhi-irc]: http://bit.ly/pydelhi-irc
[issues]: https://github.com/pydelhi/pydelhi-infra/issues
[new github issue]: https://github.com/pydelhi/pydelhi-infra/issues/new
