# magic 8 challenges

**Challenge 4**

input.onGesture(Gesture.Shake, function () {
    basic.clearScreen()
    randomNumber = randint(0, 20)
    if (randomNumber == 1) {
        basic.showString("YES")
    } else if (randomNumber == 2) {
        basic.showString("NO")
    } else if (randomNumber == 3) {
        basic.showString("MAYBE")
    } else if (randomNumber == 4) {
        basic.showString("ASK AGAIN LATER")
    } else if (randomNumber == 5) {
        basic.showString("DEFINITELY")
    } else if (randomNumber == 6) {
        basic.showString("NOT LIKELY")
    } else if (randomNumber == 7) {
        basic.showString("VERY LIKELY")
    } else if (randomNumber == 8) {
        basic.showString("CANNOT PREDICT NOW")
    } else if (randomNumber == 9) {
        basic.showString("MOST LIKELY")
    } else if (randomNumber == 10) {
        basic.showString("DON'T COUNT ON IT")
    } else if (randomNumber == 11) {
        basic.showString("OUTLOOK GOOD")
    } else if (randomNumber == 12) {
        basic.showString("MY SOURCES SAY NO")
    } else if (randomNumber == 13) {
        basic.showString("YES, DEFINITELY")
    } else if (randomNumber == 14) {
        basic.showString("YES, IN DUE TIME")
    } else if (randomNumber == 15) {
        basic.showString("REPLY HAZY, TRY AGAIN")
    } else if (randomNumber == 16) {
        basic.showString("WITHOUT A DOUBT")
    } else if (randomNumber == 17) {
        basic.showString("MY REPLY IS NO")
    } else if (randomNumber == 18) {
        basic.showString("YES BUT WAIT")
    } else if (randomNumber == 19) {
        basic.showString("VERY DOUBTFUL")
    } else {
        basic.showString("I DON'T KNOW")
    }
    basic.showNumber(8)
})
let randomNumber = 0
basic.showString("ASK A QUESTION")
basic.showNumber(8)
