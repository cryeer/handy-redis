# Snapshot report for `test\generated\commands\zlexcount.test.js`

The actual snapshot is saved in `zlexcount.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/zlexcount.md example 1

> Snapshot 1

    [
      'await handy.zadd("myzset", [0, "a"], [0, "b"], [0, "c"], [0, "d"], [0, "e"])  => 5',
      'await handy.zadd("myzset", [0, "f"], [0, "g"])                                => 2',
      'await handy.zlexcount("myzset", "-", "+")                                     => 7',
      'await handy.zlexcount("myzset", "[b", "[f")                                   => 5',
    ]
