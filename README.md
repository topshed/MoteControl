# MoteControl

### Python Flask web app for controlling Pimoroni Mote

![alt tag](https://raw.githubusercontent.com/topshed/MoteControl/master/mote.png)

####Instructions

1) Make sure you have the Mote, colorsys and Flask Python3 libraries installed.
2) For best results also install Firefox/Iceweasel:

sudo apt-get install iceweasel

You can use the app with Epiphany although the Colour Picker function will not work and some of the styling is lost.

3) Clone this repo

4) run:

python3 motecontrol.py

5) Open your browser and go to 127.0.0.1:5000

6) Select the desired lighting for your Mote (this code assumes you have the full Mote kit with 4 mote strips):

a) Rainbow - peaceful fluctuating rainbow colours

b) White (ish) - all on white

c) Sunny - a jolly yellow colour (you may need to optimise for your wall colour - mine are green so I reduced the amount of green in the mix).

d) Disco - random flashing colours. Add extra RGB tuples to the 'colours' list.

e) Strobe - headache inducing white flickering

f) Sparkles - random colours on random elements. A bit like rainbow but more glitzy

g) Stars - random single lights will gently fade up to white than fade out again.

h) Larson - Pretend your room is the Knight Industries 2000

i) Red Alert - Shields Up!

You can also set your own colour using the sliders. The motes will only update once the 'Manual' button is pressed. Or use the colour picker and then click 'Pick Set'. You can also set which of your 4 mote sticks are activated for this function. 
