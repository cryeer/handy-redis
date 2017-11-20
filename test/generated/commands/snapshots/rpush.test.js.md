# Snapshot report for `test\generated\commands\rpush.test.js`

The actual snapshot is saved in `rpush.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/rpush.md example 1

> Snapshot 1

    [
      'await handy.rpush("mylist", "hello")  => 1',
      'await handy.rpush("mylist", "world")  => 2',
      'await handy.lrange("mylist", 0, -1)   => ["hello","world"]',
    ]