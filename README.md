# vvv-wp-multisite-subdir
A sub-directory multisite install of WordPress template for VVV 2.x

## How to Install

Open up your `vvv-custom.yml` and add an entry under the sites list that looks like this:

```
  example:
    repo: https://github.com/tomjn/vvv-wp-multisite-subdir.git
    hosts:
    - example.local
```

The result will be a WordPress multisite install located at http://example.local, you can change the name from example and example.local to anything you want, so long as the two match, e.g:

```
  moomins:
    repo: https://github.com/tomjn/vvv-wp-multisite-subdir.git
    hosts:
    - moomins.local
```

You can also use this as many times as you want, here's 3 multisites:

```
  example1:
    repo: https://github.com/tomjn/vvv-wp-multisite-subdir.git
    hosts:
    - example1.local
  example2:
    repo: https://github.com/tomjn/vvv-wp-multisite-subdir.git
    hosts:
    - example2.local
  example3:
    repo: https://github.com/tomjn/vvv-wp-multisite-subdir.git
    hosts:
    - example3.local
```

## How do I version control my site?

Create your own git repo with the same contents and replace the `repo:` line to point at your new git repository
