# To measure is to know. If You can't measure it, You can't improve it - Lord Kelvin.

# A word of introduction to SCADA

I am a huge fan of Lord Kelvin's words. No self-respecting engineer will
operate in the domain of guesses, conjectures and urban legends.
Determining a solutions based on incorrect data is a direct - and yet
time wasting - path to disaster. SCADA systems (Supervisory Control And
Data Acquisition) are systems that monitor the process of an occuring
physical phenomenon and record simultaneously its related parameters.
Supervision of actual values allows you to control (interact) the
process, and in combination with engineering and data analysis
techniques, it constitutes the solid input of information for further
development work.

# Practical implementation

Leaving theory apart, how it can be practically applied? If you are a
car tuning enthusiast, I recommend you watching Gale Banks' \"Killing a
Duramax\" video series
<https://www.youtube.com/playlist?list=PLwtmrqcWzLtQsQGxE-x2i8GaPgEuItUkn>.
This is the most exact answer to what SCADA is and what is it about. In
this cycle, Gale Banks decided to experimentally check how much the
stock Duramax engine can withstand. The rule is quite simple: we monitor
the parameters of the running engine while overloading it above limits,
so that - when it is irreversibly blown - we can answer the question:
WHY DID THIS HAPPEN? And this is the practical application of the SCADA
system. I watched this series in awe of Gale's engineering level, while
also reflecting on the physical phenomena taking place there. Some
measurements - such as the measurement of cylinder pressure as a
function of crank angle - require the use of a very expensive and
specialized equipment, while determining parameters related to air
density is trivially simple. Out of pure curiosity, I decided - as an
experiment - to design and implement a practical SCADA solution that
would allow the observation of parameters.

# Table of Content

Here I will publish the consecutive materials describing:

1.  A technical walkthough the SCADA systems with pros and cons for the
    setup

2.  Based on the above, I am going to develop our system to a next
    iteration

In general, what I am looking forward is to:

1.  Familiarize You with SCADA systems from the very basics,

2.  Develop an open-source SCADA system that is going to be a practical
    implementation of the theory (that means we will dig into a data
    acquisition, visualisation, develop own SCADA system elements (like
    sensors, etc.), supporting You with schematics, PCBs and code

3.  I am going to put the efforts to use an easily accessible
    components, that are inexpensive and accurate enough to give
    satisfying results.

4.  Last but not least, I am looking forward passionates and volunteers,
    that could share their knowledge in the project like I do.

Are You interested? Fasten the seatbelt, let's see how far we can go
with a DIY project. Oh, and by the way - if You want me to ellaborate on
something, feel free to ask (You can find me on X at Hax0rZmr0cku).
