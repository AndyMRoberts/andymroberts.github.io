---
title: "Retrofitting a Child’s Toy for AI Autonomous Agriculture Research"
permalink: /projects/toy-retrofit-agriculture/
---

{% include site-nav.html %}

# Retrofitting a child’s toy for AI Agriculture Research

# 2026-04-02 - Purchasing

For my first paper after starting my PhD I looked into power performance of the ORB-SLAM algorithms ([Paper Link](https://ieeexplore.ieee.org/document/11105118)) with my focus on their use in agricultural autonomous robots. And I wanted a field test to show SLAM being used in real-time in real fields but my little Turtlebot with its back ball-bearing wheel and 1cm ground clearance wasn't able to go anywhere not nicely carpeted. If I wanted to buy a proper autonomus research robot like the [Husky](https://clearpathrobotics.com/husky-a300-unmanned-ground-vehicle-robot/) or the [Amiga](https://bonsairobotics.ai/equipment/) then I'd easily blow my PhD funding 5x over. 
So since then I've been on the lookout for something cheap and cheerful that would still be decently portable but hefty enought to mount a Jetson Nano and camera suite, as well as possibly other add-ons like manipulators, and that could drive around at least on grass to collect data in the field. 

![Even if reduced to £65.00, do not buy, it is a scam!]({% link assets/images/projects/ali-bot.png %})

After trying to buy a massively discounted remote-controlled lawnmower on Ali-Express that turned out to be a scam I thought why not just retrofit a childrens sit-on electric ATV! It has almost everything I need: handles large weight with built-in strong chasis and motors, good ground clearance, and small enought to fit in the back of a car to move to a test site without issues. On ebay I found this:

![Toy or Research Vehicle Ready to Happen]({% link assets/images/projects/ebay_brum.png %})

## The HOMCOM 12V Electric Quad Bike (with Music!)
Max Speed: 4km/h
Max Run Time: 50 mins
Battery: 12V 4.5 Ah
Motors: 12V
Wheel: Ф24cm
Material: PP and steel;
Dimensions: 50H x 88L x 45Wcm. 
Seat off the ground: 34H x 36W x 17Dcm. 
Suitable for ages 3-5 years. 
Maximum load 25kg. 

Certification: EN71-1-2-3, EN62115. 
Assembly required.

The only thing its missing is controlled steering. But this can either be resolved with a suitable integrated servo motor, or at worst, the car can be driven in reverse in skid-steering mode with the turnable wheels acting as passive back wheels. Either way there is plenty room to fit cameras, compute devices, other sensors, and even incorporate a second battery for longer run times, it even has speakers for music. 

![It even runs with me on, and I'm slightly heavier than 25kg]({% link assets/images/projects/me-on-new-roboto.jpg %})


Next Steps:
- inspect interior for best way to fit steering mechanism and incorporate autonomous steering and speed controls.


<p><a href="{{ '/projects/' | relative_url }}">← Back to projects</a></p>
