Simple command-line progress bar
=====================

`progressbar` is a simple progress bar made in BASH.

## How to use

Simple example in `test-progress-bar`, which has the following snippet:

```bash
for i in $(seq 0 10); do
    echo $i
    sleep 1
done | ./progress-bar -m 10 -w 40 -b "=" -i -t "Example "
echo "Done"
```



