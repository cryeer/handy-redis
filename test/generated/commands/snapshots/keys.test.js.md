# Snapshot report for `test\generated\commands\keys.test.js`

The actual snapshot is saved in `keys.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/keys.md example 1

> Snapshot 1

    [
      'await handy.mset(["one", "1"], ["two", "2"], ["three", "3"], ["four", "4"])  => "OK"',
      'await handy.keys("*o*")                                                      => "sorted => [ \'four\', \'one\', \'two\' ]"',
      'await handy.keys("t??")                                                      => "sorted => [ \'two\' ]"',
      'await handy.keys("*")                                                        => "sorted => [ \'four\', \'one\', \'three\', \'two\' ]"',
    ]
