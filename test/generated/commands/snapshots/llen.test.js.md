# Snapshot report for `test\generated\commands\llen.test.js`

The actual snapshot is saved in `llen.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/llen.md example 1

> Snapshot 1

    [
      'await handy.lpush("mylist", "World")  => 1',
      'await handy.lpush("mylist", "Hello")  => 2',
      'await handy.llen("mylist")            => 2',
    ]
