cache_transpose
===============

Cache based matrix transpose. If on Linux execute "Make run" to force
CPU affinity consistent results.

This source code is based on the original work done by Ian Fraser.

http://iainkfraser.blogspot.co.uk/2013/01/cache-money-hoes-attached-code.html

Output on my setup
------------------

    % make run
    taskset 1 ./transpose
    naive: 1997 1989 1991 
    cache aware: 1213 1199 1200 
    cache aware2: 1031 1017 1013 
    cache oblivous: 1366 1240 1244 

