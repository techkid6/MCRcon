MCRcon
======

Library and CLI for Minecraft's RCON Libraries

Example Usage
-------------

Using the Library:

```python
# Connect to RCON and send command
import mcrcon

rcon = mcrcon.MCRcon("localhost", 25575, "password")
rcon.send("say Hi!")
```

Using the CLI:

```
python mcrcon_cli.py -H localhost -p 25575 -P password (Interactive Prompt)
python mcrcon_cli.py -H localhost -p 25575 -P password -c "say Hi!" (Single Command, exits with command result)
```

License
-------

The original repository that this was forked from had no visible license, however, the Github Terms covers situations like this as follows

> However, by setting your pages to be viewed publicly, you agree to allow others to view your Content. By setting your repositories to be viewed publicly, you agree to allow others to view and fork your repositories.
