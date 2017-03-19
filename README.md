# building-a-touch-mirror
Instructions for building a touch enabled smart mirror.
Note: Some of these materials were used because they were what I had around, or my personal preference. This is not the only way to build a touch enabled smart mirror.

## Materials:
- Matte monitor 
  
  You are going to be deconstructing this monitor of its casing and then overlaying a touch foil and the special reflective glass. I'm choosing matte because it seemed like there was a double reflection happening when using a hard surfaced monitor together with the reflective glass. I used one of my two extra Asus monitors I had siting on my desk.
- [Raspberry Pi Model 3 B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/)
  
  I had bought my raspberry pi from Cana Kit, but that's just because it was my first one and I wanted an easy all inclusive purchase when I had got it. However, I have found that the base is nice for strapping to the back of the monitor.
- [Vanity Vision Smart Mirror Glass (70% Reflective 30% Transparent)](http://www.twowaymirrors.com/smart-mirror/)
  
  This 'two way mirror' glass will give you a mirror like reflection when your display is dark, and allow you to see the screen when/where it is lit up. I got samples of the vanity vision glass and the regular smart mirror glass and the vanity vision is definitely my preference. The regular two way mirror glass didn't provide enough transparency (11% vs 30%) compared to the vanity vision. I will get mine untempered as tempered supposedly has distortion. I also am opting for just the sanded edge as it is the cheapest option and I will have a slight border around the edge.
- [3ft DVI-D Male to HDMI Male connector](https://www.amazon.com/gp/product/B0007MWE14/)
  
  Because I am using a slightly older monitor that doesn't support hdmi, I needed a connector that would convert from the pi's hdmi to either vga or dvi-d on my monitor. I opted for dvi-d because it is a digital display and should provide clearer picture. I actually had a difficult time finding a connector that was male to male and also not ridiculously long. I finally found this 3ft version which provided an ok amount of slack to run the cable on the back of the monitor without too much coiling.
- Projected Capacitive touch foil
  
  This is definitely one of the hardest parts about this project. I wanted to go with a projected capacitive touch foil over an IR touch sensor because the PC option has a thinner bezel, is installed behind the glass, is the same tech as smartphones use, and doesn't have sunlight interference light IR does.
  
  However, finding a company that would sell a single touch foil has proved dificult. I contacted Displax and Zytronic with no response from either. Finally I found another company, [Xinttec](http://www.xinttec.com/English/index.html) which would actually respond to my request via email. They claim their touch foil drivers only support ubuntu, and didn't respond on clarification if ARM7 architecture would be a problem, and if Ubuntu MATE would be suitable. I will have to get back/confirm on this one.
