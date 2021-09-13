This is a forked/modified version of [SlidingRuler](https://github.com/Pyroh/SlidingRuler) 

```Swift
@State private var value: Double = 0

var body: some View {
    ...
    SlidingRuler(value: $value)
    ...
}
```

Note that `value` must conform to `BinaryFloatingPoint`.
