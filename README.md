# HermesIOT
This is the software framework for a Windows (10) IOT platform design to manage and host IOT experiments going into harsh environments

This is where the Hermes IOT software framework will be hosted post launch of the Quest International platform slated for mid-year 2016. The framework was designed in collaboration with students Valley Christian School and engineers at Quest. The purpose of the platform was to create an easily programmable IOT platform supporting digital I/O, analog input and monitoring of the overall platform such as temperature, humidity, power draw and voltage to the platform as well as the student experiment. 

Coupled with this software framework is a jointly-designed hardware shield mated to an Intel x86 Minnowboard Max. The schematics, shield information (such as parts list) and firmware watchdog code will be in a separate repository but ultimately referenced here. Aside from hosting sensors the shield also does two other major things; it monitors a digital pin toggle from the software framework (known as the heartbeat) and will power cycle the MinnowBoard in the event of heartbeat loss. The second thing is that the shield can host up to 8 total bootable USB sticks the purpose of which is to provide a way for the platform to function even though the platform has suffered radiation event that rendered the current running USB stick corrupt. In this way the platform allows for 7 failures before the platform is at risk for total loss. Refer to the platform and shield docs to get the specifics on what the failure protocols and tolerances are (once the designs and code are in these repos).

Post launch all code and shield designs will be in these two repositories. The intention is for any individual, company or school to take the code and designs, outsource manufacturing of the shield and then customize the code + shield to their particular situation. 
You can get more information on partnering with Quest with your school or organization by finding contact information on this link: http://questforspace.com/ 


