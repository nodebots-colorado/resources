# UNDERSTANDING ELECTRICITY

## INTRODUCTION

Fortunately, you don't need a degree in electrical engineering to work with microcontrollers. But it is helpful to have a general understanding about how electricity and electrical systems work.

## A HYDRAULIC SYSTEM AS AN ANALOGY

Electricity and electrical systems can at first seem a bit complex, but it can helpful to think of it in terms of how water systems work. For a very simple example, think about water coming out of a hose. The water moving through the tube has a direction, current, pressure, and resistance. Resistance can be caused by turning the valve or kinking the hose.

Electricity is very similar to this. When you plug in a lamp, electrons travel between atoms flowing through the cord, to the filament in the lightbulb and back down through the cord to the socket where it is grounded. This electrical current has a direction, pressure caused by the width of the wire, and resistance caused by the material it's flowing through. In the world of electricity, we talk about these concepts as volts, amps, and ohms.

## AC & DC

Okay, I kind of lied to you about current in my lamp example, but it was for a good reason. DC is a little easier to wrap your head around. But your lamp, like most things your plug into your home use alternating current (AC), for which we have Nikola Tesla to thank. Alternating current actually doesn't travel in one direction. It travels backwards and forwards. Whereas direct current only travels in one direction. A good rule of thumb is anything that uses a battery is direct current, and anything you plug into a wall is alternating current.

There are some notable exceptions such as laptops, which use DC for their battery power, and they convert the AC from the socket to DC. Also, flatscreen TV's with LEDs convert to DC, because LEDs care about the direction of electrical current.

There are a lot of interesting facts about how AC and DC work, why we use one instead of the other, as well as the history behind the two (Edison electrocuting animals to discredit Tesla being one of them). But, for the sake of brevity, I'll leave it at that. However, you should look into it more if you're interested.

## VOLTS, AMPS, AND OHMS

A lot of this information is from [Getting Started with Arduino]("http://it-ebooks.info/book/4882/"), which I highly recommend as a resource, especially pages 37-40 for a better explanation of how electricity works.

Voltage is the equivalent of water pressure. Think of a little AA battery. It can only push out 1.5 volts of pressure through the wire, where as a 9 volt can push with a lot more force.

Current is measured in amperes, or amps. The current is just like the current of water. It's the amount that can flow through. Having higher amperage allows more electricity to flow at one time so it can potentially deliver more power at any given time.

Resistance is measured in ohms, and it's caused by the wires. If you imagine the wires as the pipes electricity flows through, a narrow wire is like kinking the hose. And some of the resistance is due to the wires themselves. Some of the electricity is lost to heat and the material itself. This resistance is relatively in materials like copper or silver, which are conductors, but in insulators like plastic or wood, the resistance is very high.

Herr Ohm discovered this principle and this equation to describe the relationship between resistance, current, and pressure.

`R (resistance) = V (voltage) / I (current)`

This equation can be helpful down the road for projects. And again, if you're wanting to learn more about this, [Getting Started with Arduino]("http://it-ebooks.info/book/4882/"), does a much better job explaining it. But hopefully this gives you enough to be familiar with the terms.
