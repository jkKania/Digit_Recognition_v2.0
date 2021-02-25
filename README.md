# Digit_Recognition_v2.0

Application `recognizes numbers` drawn on it's canvas using `FANN` artificial intelligence `(AI)` library.

## How to work with the application

Application is meant to be used together with a learning base *.data file which configures neural network 
of the app in order to recognize digits properly.

File `*.data` (learningBase.data) is attached in `bin/Debug` and app by `default` uses this location as a `source of knowledge`. 

However it can be `genrated using` another project in `my GitHub` repository named  [GeneratorBitMap](https://github.com/jkKania/GeneratorBitMap) where user 
can simply draw numbers by hand in order to `personalize` apps `recognition` skill for users `style of writing`.

`Generator` will (as the name suggests) generate a file *.data for you so you could just simply attach it to `Digit Recognition`,
load it to memory, train the neural network annd finally draw numbers and let applciation reognize it

---

## Sample application workflow:

- User loads and trains neural network using button `Train!` or `Train from file !`
- User draw digits on canvas and clicks `Compare !` button 
- Application prints the result digit with the highest calculated probability
