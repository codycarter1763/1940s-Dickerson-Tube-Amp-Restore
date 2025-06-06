# 1940s Dickerson Tube Amp Restore

<p align="left">
  <img src="https://github.com/user-attachments/assets/645d1149-88da-4d76-9d55-1ae71cb736c1" width="48%" height="48%" alt="Left Image">
  <img src="https://github.com/user-attachments/assets/7ed48e65-59fb-4d7f-88f8-652cb52f060e" width="48%" height="48%" alt="Right Image">
</p> 


# About
This is a build log on a restoration of a salvaged 1940's Dickerson tube amp. The amp came from my grandparents who were always collecting vintage jukeboxes, arcade machines, slot machines, vending machines, and other vintage electronics. The amp came from my great grandparents who were New Orleans musicians and part of a band where they both were in a band playing lap steel guitar and accordion in the 40's through 50's. When I stumbled on this vintage tube amp, I knew that this would be the perfect project to learn about vacuum tubes, amp restoration, and have the opportunity to bring new life to such legendary gear. 

<p align="left">
  <img src="https://github.com/user-attachments/assets/0cc5638d-2aa4-4626-9a4b-37657408b8c1" width="48%" height="48%" alt="Left Image">
  <img src="https://github.com/user-attachments/assets/976be195-f448-4a44-baa0-f8da2c6d56ec" width="48%" height="48%" alt="Right Image">
</p> 

![I6](https://github.com/user-attachments/assets/198c0680-5f02-4732-88bc-0f84088d126a)

# History Of Dickerson
Dickerson amplifiers was founded in Southern California by Delbert J. Dickerson and played a huge role in developing amplifiers that were the precursor to the legendary Magnatone brand. The inspiration came from finding a solution to making an electric lap steel guitar and amp for his daughter. With this being the first electric instrument to be patented, this idea caught on fast. Originally designed for Hawaiian guitarists in Southern California, this was one of the first mass-produced steel and amp combos that was commercially successful. 

![US2209016-drawings-page-1](https://github.com/user-attachments/assets/947f42c8-c1a2-40a2-aa15-833724704f0d)

After the shift to Magnatone, business started booming and more units were being sold. Artists such as Buddy Holly, Paul Bigsby, and Lonnie Mack were the early pioneers of Magnatone and helped release new amp technology that created a distinct vibrato reverb. The legacy and history of these amps span a long period of time and have inspired many lap steel, accordion, harmonica, and so many more players. 

For this amp in particular, this model was created in 1947 and used a single-ended design with 6V6 power tubes, Rola field-coil speaker, two inputs, and 5 watts of power. This model was known for its' driven overdrive tone and is comparable to early Supro and Fender Champ amplifiers. The outside finish has a green "mother of pearl" or also known as "mother of toilet" that is very distinct. 

![xwptxyadbov9wfzcqrk0](https://github.com/user-attachments/assets/4c508ae7-564b-4e98-88d6-9b25a5cf652f)

![053aee929880d18f6db7836267eed1d4](https://github.com/user-attachments/assets/f0572574-6d4e-437d-b583-5f17b63c8821)

# Restoration Process
For this amplifier restoration, I have opted to keep everything as original as possible, only replacing the necessary components to preserve the aesthetics and reliably operate. Since this amp used oil capacitors and carbon composition resistors, the components all tested out of tolerance so I replaced those components with their more modern electrolytic and metal film and carbon film counterparts. 

Before ordering the components, I tested for continuity and proper resistance for all of the transfromers and speaker coils. Thankfully, everything was still operational.

### Completed Rewiring
![IMG_6](https://github.com/user-attachments/assets/f2c4b995-21c1-489b-9592-f2b5210dec96)

## Schematic Diagram and Analysis
As the circuit inside the amp was slightly different than any other schematic that I could find online, I traced out the circuit diagram to see what I was working with. 

![Dickerson Amp Schematic Fixed V2_page-0001](https://github.com/user-attachments/assets/20c55132-d040-475d-8202-8a2ac99a5e0b)

The design follows a single-ended 6V6 design operating as a Class A amplifier and producing 4 to 5 watts of power. Especially when driven with pedals, this amp puts out some serious volume with a smooth, harmonically rich sound. 

### Input Stage
The input stage uses a 6SJ7 pentode tube that will boost the signal enough to be fed into the 6V6 power stage. Since the amp was mostly used for lap steel, accordian, and harmonica, I switched the 510k resistor to a 1Meg resistor to prevent tone sucking from the guitar signal. 

Connected to pin 5 of the 6SJ7 is an RC network that attenuates the guitar signal with a cutoff of 16Hz and sets the tube bias.

fc = 1 / 2pi(10uF)(1kOhm) = 15.92Hz

![image](https://github.com/user-attachments/assets/3c61ea07-2b16-4e17-8fad-9113f64b30e7)

## Power Stage
The power stage uses a 6V6 tube and operates in a single ended configuration where the tube amplifies both the positive and negative peaks of the signal, resulting in a warm tone with tube overdrive capability. 

The output from pin 3 feeds to an output transformer that converts the high impedance output signal to a low impedance signal and removes the high voltage DC offset applied to the amplified AC signal. This also acts as a choke for the power supply that will store current in the primary coil of the transformer and release it if extra power is needed. Such configuration eases the load off of the power supply and vacuum tubes.

The speaker used is called a field coil speaker used before permanent magnet speakers became widely used. The high voltage DC signal from the rectifier tube provides the power needed to power the electromagnent in the speaker. These types of speakers are known for their dynamic and warm distinct tone. 

On pin 8 of the 6V6, an RC network attentuates the guitar tone to 27Hz, increases gain, and sets the bias. 

fc = 1 / 2pi(20uF)(300) = 26.53Hz

![image](https://github.com/user-attachments/assets/c7252280-de1f-4980-8dd1-23261756daff)

## Power Supply Stage
The power supply stage uses an iso-transformer to convert the 120VAC from the wall to the various voltages needed for operation. The 365VAC signal is rectified to DC with a 5Y3GT rectifier tube for the amp. The infamous .05uF death cap was removed in the final restoration due to safety concerns if the capacitor fails where 120VAC can be shorted to ground. I also upgraded to a 3 prong cable for added safety since the chassis will be grounded.

Instead of the three capacitor can capacitor, I opted to just replace it with three seperate 20uF electrolytic capacitors. Such designs were used back in the day to save space and money, though with reliable and cheap capacitors nowadays you can use seperate capacitors. As a result, I was able to install the capacitors close to the power suppply rails to reduce noise. To keep the vintage look, I left the can capacitor installed in the socket. 

![image](https://github.com/user-attachments/assets/109a167c-b60a-40f8-aa88-a3e28b3a9b0c)

# Aesthetics
The condition of the amp was super rusted and dirty when I first received it. In an effort to preserve the original finish and logo, I took extra care in the cleaning process. For the metal chassis, I used a wire brush and WD-40 to remove a large portion of the rust. I was not able to get all of the rust off, but it already looks so much better without having to repaint the chassis. The handle was sanded and soaked in Muriatic Acid for 24 hours which removed all of the rust for a brand new finish. 

For the mother of pearl vinyl, I used mineral oil and a soft towel to carefully clean and restore the finish. Contact cement was also used to place back the peeling parts of the vinyl. 

# Finished Product
This amp really came a long way and I learned a ton on how vacuum tubes work and the restoration process. Super happy that I was able to bring new life to such a vintage amp! The amp sounds great on its' own and even better when driven with a tube screamer, fuzz face, or Klon type overdrive. 

As I make any upgrades or updates, I will update this repository.

Here are some good resources that I used to help restore this amp.

https://www.reddit.com/r/GuitarAmps/comments/1ksckc8/found_this_1940s_dickerson_tube_amp_is_it_worth/

https://www.reddit.com/r/ToobAmps/comments/1kvfkn3/1940s_dickerson_tube_amp_restore_quick_question/
