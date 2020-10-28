# testing

## Toodle doodle

Trekk blokkene inn for å skru av og på LED

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```

##Hele greia

Gjør mer

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```
