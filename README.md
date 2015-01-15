# maybe-run

Display scripts and ask whether to run them.
Useful for scripts you've downloaded off the internet e.g.

    $\curl http://example.com/some-script.sh | maybe-run sh
    Command: sh
    What do you want to do with the input?
    (s)how    (r)un     (q)uit
    s

    echo I am not very good at installing things

    Command: sh
    What do you want to do with the input?
    (s)how    (r)un     (q)uit
    r
    I am not very good at installing things

The code has bits taken from the post by Darian Moody, as linked below.

To see what problems this fixes:

* [Don't Pipe to your Shell](http://www.seancassidy.me/dont-pipe-to-your-shell.html)
* [Protect yourself from the hidden dangers of `curl <url> | sh`](http://www.djm.org.uk/protect-yourself-from-non-obvious-dangers-curl-url-pipe-sh/)
