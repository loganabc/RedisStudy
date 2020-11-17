Redis支持5种数据类型：string(字符串)，hash（哈希），list（列表），set（集合），zset（有序集合）
* string是redis最基本的类型，可以理解成Memcached一模一样的类型，yigekey对应一个value。value其实不仅是String，也可以是数字。string类型是二进制安全的。意思是redis的string可以包含任何数据，