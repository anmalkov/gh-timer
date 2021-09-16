# gh-timer

A gh extension that runs timer or stopwatch

## installation

`gh extension install anmalkov/gh-timer`

## options

`gh timer [units] [number] [mode] [clock]`

#### [units]
`-s, --sec` - seconds

`-m, --min` - minutes

#### [mode]
`-w, --stopwatch` - use a stopwatch mode, otherwise use a timer mode

#### [clock]
`-b, --big` - show a big clock, otherwise show a small clock

## usage examples

`gh timer -s 10`
run a timer for 10 seconds

`gh timer -m 5`
run a timer for 5 minutes

`gh timer -m 5 -b`
run a timer for 5 minutes and show big clock

`gh timer -m 60 -w`
run a stopwatch for 1 hour

`gh timer -h`
show help

## author

Andrew Malkov <an.malkov@outlook.com>
