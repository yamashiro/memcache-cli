A simple python wrapper for python-memcached to make an easy to use command line tool.  For now it just provides access to the basic public runnable commands from the library.  In the future I may add additional helper commands such as get_hit_rate.

A big thanks to Tyler (@tghw) from FogCreek for posting the Redis Tutorial that got me started.

http://tghw.com/blog/cheeky-python-a-redis-cli/

Usage:

python memcache-cli.py host1:port host2:port


Suggestion:

It may be simpler to wrap this with a simple shell script that has your preferred connection parameters.

