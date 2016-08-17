Simple command-line progress bar
=====================

`progressbar` is a simple progress bar made in BASH.

## Options for `progressbar`

    -h              Print this help.
    -t title        Set the title.
    -m n            Set the maximal progress value (default 100).
    -w n            Set the width of the progress-bar (default 30).
    -b c            Set the progress-bar character (default #).
    -n              Put the new line at the end of the output.
    -c              Do not clear line at the end of the output.
    -i              Hide the cursor.

## How to use

Simple example in `test-progress-bar`, which has the following snippet:

```bash
for i in $(seq 0 10); do
    echo $i
    sleep 1
done | ./progress-bar -m 10 -w 40 -b "=" -i -t "Example "
echo "Done"
```



