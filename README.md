# 42fs
42 - the ultimate filesystem of life, the universe and everything.

# Usage

Don't forget to install `fusepy`:

```bash
pip install fusepy
```

Then create some source:

```bash
mkdir /tmp/src /tmp/dst
echo "Hello, world!" > /tmp/src/file
```

And then just mount and use:

```bash
./42fs /tmp/src /tmp/dst
diff /tmp/{src,dst}/file
```

That's it.

The Ultimate Filesystem of Life, the Universe, and Everything.

# Thanks

The main author is [Stavros Korokithakis](http://www.stavros.io/posts/python-fuse-filesystem/), I just applied minor modification to work it as a joke.
