# Snapshot report for `test\generated\commands\lpop.test.js`

The actual snapshot is saved in `lpop.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/lpop.md example 1

> Snapshot 1

    [
      'await handy.rpush("mylist", "one")    => 1',
      'await handy.rpush("mylist", "two")    => 2',
      'await handy.rpush("mylist", "three")  => 3',
      'await handy.lpop("mylist")            => "one"',
      'await handy.lrange("mylist", 0, -1)   => ["two","three"]',
    ]
