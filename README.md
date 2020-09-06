
# ArduinoAD8232EKG

> A python gui with recording and data manipulation for an arduino AD8232 based ekg.

---
## Table of Contents (Optional)

> If your `README` has a lot of info, section headers might be nice.

- [Intro](#intro)
- [Installation](#installation)
- [Features](#features)
- [Contributing](#contributing)
- [Team](#team)
- [FAQ](#faq)
- [Support](#support)
- [License](#license)


---

##Introduction

A quick look at where to place the electrodes:

![Image of Placement](https://github.com/ChrisDavi3s/arduino_ekg_gui/blob/master/electrode%20placement.png)

---

## Installation

**The arduino side**

- Flash the .ino to your arduino. Ensure that all the data pins are correct.
These three lines will need changing depending on which pins you decide to use. If in trouble just search google for a AD8232 arduino wiring diagram :)

```c++
pinMode(10, INPUT); // Setup for leads off detection LO +
pinMode(11, INPUT); // Setup for leads off detection LO -
Serial.println(analogRead(A0));
```

**The python side**

- Anaconda navigator was installed for my setup. Run the 


- All the `code` required to get started
- Images of what it should look like

---

## Contributing

> To get started...

### Step 1

- **Option 1**
    - 🍴 Fork this repo!

- **Option 2**
    - 👯 Clone this repo to your local machine using `https://github.com/joanaz/HireDot2.git`

### Step 2

- **HACK AWAY!** 🔨🔨🔨

### Step 3

- 🔃 Create a new pull request using <a href="https://github.com/joanaz/HireDot2/compare/" target="_blank">`https://github.com/joanaz/HireDot2/compare/`</a>.

---


## FAQ

- **How do I do *specifically* so and so?**
    - No problem! Just do this.

---

## Support

Reach out to me at one of the following places!

- Website at <a href="http://fvcproductions.com" target="_blank">`fvcproductions.com`</a>
- Twitter at <a href="http://twitter.com/fvcproductions" target="_blank">`@fvcproductions`</a>
- Insert more social links here.

---

## Donations (Optional)

- Buy me a coffee if you ever meet me.

---

## License and other important things

- This is not for medical use. I have made this for fun and any results should not be relied on. If in doubt please seek professional medical advice (ie not mine). No responsibility will be accepted for any harm that is caused by use of this code as per the licence agreement. 




