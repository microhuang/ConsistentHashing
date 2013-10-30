ConsistentHashing
=================

http://blog.codinglabs.org/articles/consistent-hashing.html


h = Hash(key) % N       ====>     h = Hash(key) % (N-1),   h = Hash(key) % (N+1)


server -> hash: hash(ip)
data -> hash: hash(key)
