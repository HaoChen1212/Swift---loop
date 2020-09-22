# Swift---loop 
use a for loop to repeat a rotating pattern

func turnaround (){
    turnLeft()
    turnLeft()
}

for i in 1 ... 2 {
    moveForward()
    moveForward()
    toggleSwitch()
    turnaround()
    moveForward()
    moveForward()
}

turnLeft()

for i in 1 ... 2 {
    moveForward()
    moveForward()
    toggleSwitch()
    turnaround()
    moveForward()
    moveForward()
}
