## How to use

1. Copy data/PHP_PMD/resources/rulesets/sutra.xml to somewhere, or copy the contents to an existing ruleset.
2. Place the PHP directory in path that is in your PHP include_path.
3. Use like so:

```bash
phpmd className.php text /path/to/sutra.xml
phpmd className.php text /path/to/ruleset-with-sutra-rules-copied-in.xml
```

## Gentoo

Coming soon. In the meantime, install my overlay (it will be there):

https://github.com/tatsh/tatsh-overlay
