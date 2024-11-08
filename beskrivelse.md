# Trekk på kode for å få motoren til å spinne

## Åpne motorblokken
Bruk ulik kode for å gjøre dette
Bruk blokken ``||basic:pause||`` og blokken ``||servos:SettVinkelPåServo||`` og plasser dem i gjenta for alltid blokken.
```blocks
basic.forever(function () {
servos.P0.setAngle(90)
basic.pause(100)
```

## Gå til steg 5 for å se forslag på løsning

## 3

## 4

## 5 ferdig kode

```blocks
basic.forever(function () {
        servos.P0.setAngle(30)
        basic.pause(1000)
        servos.P0.setAngle(150)
        basic.pause(1000)
```