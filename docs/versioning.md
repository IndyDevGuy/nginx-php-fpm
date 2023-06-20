## Versioning
We are now introducing versioning so users can stick to specific versions of software. As we are dealing with three upstream sources (nginx, php and alpine) plus our own scripts this all gets a little complex, but this document will provide a definitive source of tags and versions.

We will use the [semver](http://ricostacruz.com/cheatsheets/semver.html) style notation for versioning:

>This follows the format MAJOR.MINOR.PATCH (eg, 1.2.6)
>
- MAJOR version changes to nginx, php-fpm, alpine or potential breaking feature changes
- MINOR version changes to nginx, php-fpm or scripts that are still backwards-compatible with previous versions
- PATCH version minor changes and bug fixes

### Current versions and tags

The latest tag will always follow the master branch in git. the other versions will have releases attached.

#### PHP 7.2

| Docker Tag | GitHub Release | Nginx Version | PHP Version | Alpine Version | Container Scripts |
|------------|----------------|---------------|-----------|--------|--------|
| 1.0.0      | 1.0.0          | 1.14.0        | 7.2.4     | 3.6 | 0.3.6 |
| 1.0.1      | 1.0.1          | 1.16.1        | 7.4       | 3.6 | 0.3.6 |

These tags will be created as releases on GitHub and as tags in docker hub.

