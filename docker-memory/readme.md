# container memory usage
docker stats show memory usage including cache meaning that most of the time, a lot of the memory can be allocated by the processes which is done transparently at the os level by decreasing the cache.

this script show the reserved memory of the container processes / os processes.
