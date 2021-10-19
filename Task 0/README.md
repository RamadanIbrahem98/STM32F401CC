# Task 0

- [ ] The system is consisted of 1 LED and 1 push button.
- [ ] The LED shall be connected to PORTB pin number 2 (OC0).
- [ ] The push button shall be connected to PORTB pin number 0 with a pull down resistor.
- [ ] switch is active low.
- [ ] The Software shall check the state of the push button periodically.
- [ ] Button shall be considered pressed, if the pin value is held low for at least 50ms.
- [ ] Software shall not consider a new button press before it is released first.
- [ ] The LED shall be controlled via PWM channel.
- [ ] The LED power shall be changed by the change of the duty cycle.
- [ ] The LED signal duty cycle shall be split into 10 steps (10% each).
- [ ] Upon each button press, the LED duty cycle shall be incremented by one step.
- [ ] If the last value of the duty cycle is 100%, the next step will be 0.
- [ ] The LED signal period shall be 2 ms.

## Run the Application

```sh
make
```

## Clean

```sh
make clean
```
