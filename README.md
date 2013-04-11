BukkitFormatter
===============

Unofficial formatter for CraftBukkit code. This is **not** a replacement for checking your diffs for trailing spaces before submitting a PR.
Unfortunately, this will not format your `// CraftBukkit` comments ;-)

### Known Issues
Eclipse will put a trailing space in the following situation, at the `#` symbol:
```java
/**
 * Lorem ipsum dolores.
 *#
 * @returns Foobar
 */
```
