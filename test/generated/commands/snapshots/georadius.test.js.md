# Snapshot report for `test\generated\commands\georadius.test.js`

The actual snapshot is saved in `georadius.test.js.snap`.

Generated by [AVA](https://ava.li).

## scripts/redis-doc/commands/georadius.md example 1

> Snapshot 1

    [
      'await handy.geoadd("Sicily", [13.361389, 38.115556, "Palermo"], [15.087269, 37.502669, "Catania"])  => 2',
      'await handy.georadius("Sicily", 15, 37, 200, "km", "WITHDIST")                                      => [["Palermo","190.??"],["Catania","56.??"]]',
      'await handy.georadius("Sicily", 15, 37, 200, "km", "WITHCOORD")                                     => [["Palermo",["13.??","38.??"]],["Catania",["15.??","37.??"]]]',
      'await handy.georadius("Sicily", 15, 37, 200, "km", "WITHDIST", "WITHCOORD")                         => [["Palermo","190.??",["13.??","38.??"]],["Catania","56.??",["15.??","37.??"]]]',
    ]
