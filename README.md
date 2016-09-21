# emojitable

> Fixed-size Hash Map written in native Emojicode.

This package was written for and has been tested with Emojicode v0.3 only.

# Installation

```bash
$ # Download and setup Emojicode.
$ make install
$ # Run tests on this package.
$ make test
$ # Run a stress test on this package (don't expect much 😁).
$ make stress-test
```

# Example Code

```
👴 Initialize a new emojitable (📰) of size 10 that stores String (🔡) keys.
🍦 table 🔷 📰🐚🔡 📝 10

👴 Insert the key-value pair, ("Hello", "World"). Returns true (👍) on success.
🍦 success ✏ table 🔤Hello🔤 🔤World🔤

👴 Fetch the value that is mapped to by "Hello". Returns an optional (🍬).
🍦 value 📖 table 🔤Hello🔤

👴 Delete a key-value pair. Returns the value that was deleted as an optional (🍬).
🍦 deleted-value 🗑 table 🔤Hello🔤

👴 Get the load factor of the hashmap. Returns a double (🚀).
📈 table
```

# Uninstallation

```bash
$ # Remove the emojitable package.
$ make uninstall
```
