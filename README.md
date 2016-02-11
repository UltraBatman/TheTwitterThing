# TheTwitterThing
A Twitter to GPIO skeleton for nodejs programmers

This code uses a synchronous GPIO signal embedded within an asynchrnous twit stream

Modular Design:

1. Make node server on a Pi, pcduino, or other GPIO equiped device, what is GPIO? (http://tinyurl.com/GPIOdesc)

2. Connect server to a twitter account and begin tracking tweets, we use the Twit API by ttezel 

3. Connect nodejs code to GPIO outputs on pi, using onoff package (npm install onoff)

4. Connect GPIO signals to some real world components, eg Motors, LEDs, things, circuits [Up to you!]


