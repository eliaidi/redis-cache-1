MyBatis Redis Extension
=========================

[![Build Status](https://travis-ci.org/mybatis/redis-cache.svg?branch=master)](https://travis-ci.org/mybatis/redis-cache)
[![Coverage Status](https://coveralls.io/repos/mybatis/redis-cache/badge.svg?branch=master&service=github)](https://coveralls.io/github/mybatis/redis-cache?branch=master)
[![Dependency Status](https://www.versioneye.com/user/projects/5619b547a193340f3200063c/badge.svg?style=flat)](https://www.versioneye.com/user/projects/5619b547a193340f3200063c)
[![Maven central](https://maven-badges.herokuapp.com/maven-central/org.mybatis.caches/mybatis-redis/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.mybatis.caches/mybatis-redis)
[![License](http://img.shields.io/:license-apache-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

![mybatis-redis](http://mybatis.github.io/images/mybatis-logo.png)

MyBatis-Redis extension Redis support for MyBatis Cache.

Essentials
----------

* 配置文件redis.properties 
host=localhost:7000,localhost:7001,localhost:7002
timeout=5000
clientName=

* <cache eviction="LRU" flushInterval="180000" readOnly="false" size="9216" type="org.mybatis.caches.redis.RedisCache">
  </cache>
