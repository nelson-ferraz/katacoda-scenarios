Let's add the player:

```perl
my $player = {
    location => 'entrance',
    alive    => 1,
};

say Dumper $player;
```

Run the script again (`perl advent.pl`) and you should see this output:

```
$VAR1 = {
    location => 'entrance',
    alive    => 1,
};
```
