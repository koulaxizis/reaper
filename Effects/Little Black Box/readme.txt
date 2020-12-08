Little Black Box Distortion
===========================

This is my latest guitar preamp distortion, and will most likely be my last for a while.

After a lot of experimenting, I finally found a distortion function which I like:

spl0 = atan(sign(spl0) * pow(abs(spl0 * gain * 50000), brown)) * cos(atan(spl0));   

Where, gain is 0..1, and brown is usually 3.

I was going to release this without an equaliser stage, but, I ended up adding 5 peak eq's preset to the frequencies of a mesa boogie. You can change the frequencies and bandwidth as you want.

There isn't much else to say. This is currently the best I have ATM, and in my opinion is a lot better than other preamps for what I want.

I recommend the “Blackat Leon S7.wav” impulse response from BestpluginsAmpsIRPack2. I have included the wav file with this zip, but I recommend you download as many IR's as you can find, so you can choose what suits you.

I use NadIR to process impulse responses.

Have fun. Hope it works for you

Derek
 
