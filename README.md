ansible-devenv-example
======================

Example development environment produced by ansible

## How do I run it?

### Install ansible locally

```
# for OS X
$ brew install ansible
```

### Vagrant up!

```
$ vagrant up
```

## How do I access it?

After you've run `vagrant up` and the build process completes:

```
$ vagrant ssh
```

## How do I iterate?

If you change the ansible config and want to apply it, just:

```
$ vagrant provision
```

## What should I modify?

Pretty much everything you want to.

Start by modifying `site.yml`, replacing your user information.  Then go from there.


