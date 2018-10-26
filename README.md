# sonic_pi_improv
Code used to simulate improvisational structure of "trading eights" with Sonic Pi

This code was developed to be interactive with a real life instrument, in my own case, the guitar. Sonic Pi starts by playing a chord progression while the musician can solo over it. After 8 measures, Sonic Pi then simulates an improvised solo. The solo is set to end once the total sum of the note values it has played passes 15.5. At this point it will stop playing and wait for the 8 measures to complete before going back to playing the code progression.

A video of this code in action can be seen here: https://www.youtube.com/watch?v=_YRF9dtmA84&lc=z22mtvqamkatw3epi04t1aokgpnmvgjfurtbut5pkweubk0h00410

Be aware that this code does include Ruby code that isn't part of the Sonic Pi language and is subject to not work after any given version update.
