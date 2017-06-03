# Expect scripts
Two `expect` scripts I'm using on a daily basis for connecting through `SSH` to many remote Linux hosts and to download files (logs mostly) from them using `scp`

The reason why authentication by the password is used within the scripts is because each day I connect to multiple different hosts. And very rare to the same host two days in a row.

Since all the hosts has consistent naming and predictable output during the connection establishment, `expect` is working quite fast and reliable in such circumstances.
