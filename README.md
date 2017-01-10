# vvv-wp-multisite-subdir
A sub-directory multisite install of WordPress template for VVV 2.x

## How to Install

Open up your `vvv-custom.yml` and add an entry under the sites list that looks like this:

```
  example: https://github.com/tomjn/vvv-wp-multisite-subdir.git
```

The result will be a WordPress multisite install located at http://example.local, you can change the name from example and example.local to anything you want, so long as the two match, e.g here's a http://moomins.local multisite:

```
  moomins: https://github.com/tomjn/vvv-wp-multisite-subdir.git
```

You can also use this as many times as you want, here's 3 multisites:

```
  example1: https://github.com/tomjn/vvv-wp-multisite-subdir.git
  example2: https://github.com/tomjn/vvv-wp-multisite-subdir.git
  example3: https://github.com/tomjn/vvv-wp-multisite-subdir.git
```

This will create 3 multisites at http://example1.local, http://example2.local and http://example3.local

## How do I version control my site?

Create your own git repo with the same contents and replace the `repo:` line to point at your new git repository
