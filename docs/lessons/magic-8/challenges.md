# magic 8 challenges

input.onGesture(Gesture.Shake, function () {
    basic.clearScreen()
    randomNumber = randint(0, 8)
    if (randomNumber == 2) {
        basic.showString("YES")
    } else if (randomNumber == 1) {
        basic.showString("NO")
    } else if (randomNumber == 3) {
        basic.showString("DEFINATELY")
    } else if (randomNumber == 4) {
        basic.showString("MAYBE")
    } else if (randomNumber == 5) {
        basic.showString("NO WAY")
    } else if (randomNumber == 6) {
        basic.showString("POSSIBLE")
    } else if (randomNumber == 7) {
        basic.showString("TRY AGAIN")
    } else if (randomNumber == 8) {
        basic.showString("SORTA")
    } else {
        basic.showString("I DON'T KNOW")
    }
    basic.showNumber(8)
})
let randomNumber = 0
basic.showString("ASK A QUESTION")
basic.showNumber(8)


