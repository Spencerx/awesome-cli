# cpulimit

* Homepage: https://github.com/opsengine/cpulimit

cpulimit is a simple program that attempts to limit the CPU usage of a
 process (expressed in percentage, not in CPU time). This is useful to
 control batch jobs, when you don't want them to eat too much CPU. It does
 not act on the nice value or other priority stuff, but on the real CPU
 usage.  Besides it is able to adapt itself to the overall system load,
 dynamically and quickly.
