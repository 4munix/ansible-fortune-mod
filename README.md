Tested on

![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)

fortune-mod
=========

Compile and install fortune-mod from https://github.com/shlomif/fortune-mod.


Role Variables
--------------

| variable | description |
| ---      | ---         |
| `packages_redhat` | packages needed for Red Hat |
| `dest_dir` | Destination directory |
| `release` | which release to use |
| `file_extension` | .tar.xz |
| `build_dir` | build directory must be created |
| `download_url` | Where to fetch the release from |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - fortune-mod

License
-------

MIT

Author Information
------------------

4munix
