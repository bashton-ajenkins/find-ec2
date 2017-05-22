# mg-find-ec2

A python script to generate a file from a template, with hosts found by
EC2 tag.

We use this where we might otherwise used Puppet stored configuration.

## Packaging

To package mg-find-ec2 a script is provided in the repository, to use it just run:

```
./package.sh <package version number> <package revision>
```

from the root of the repository.

For example if I want to create a package with the version number 3.0.1 and I made a mistake with the last package for that version I would do:

```
./package.sh 3.0.1 2
```

This will then create mg-find-ec2-3.0.1-2.noarch.rpm.
