# 2 Speed Gearbox

This mechanism alters the input speed from the power source using gear ratios.
I chose it due it's simplicity and practicality in real life(the most well known use being for automobiles)

## How it works

```
The mechanism is powered by the lever spining the first axle that moves freely from it's cogs using the bearings. The ring on the axle spins with it and moving it determines the state of the machine.
In neutral state the ring doesn't interact with any cog so no movement is transmited to the rotor. 
In first gear the ring goes near the small cog and moves it, the small gear will spin a bigger gear that is connected to the 2nd axle that moves the rotor. Due to gear ratio the second axle with the big gear will have less rotational speed than the first.
In second gear the ring goes near the big cog and moves it, the big gear will spin a smaller gear that is connected to the 2nd axle that moves the rotor. Due to gear ratio the second axle with the small gear will have more rotational speed than the first.
```
## Components and Joints

```
Important-Components:
wall-suports the machine
ax2, ax1- the axles
ring- the component used to shift the gears
Gear-Big/Small 1- gears on the first axle with bearings so that the axle can move independently
Gear-Big/Small 0- gears on the second axle that move with the axle

Joints:
(revolute)Ax2-B:Moves the firstt axle
(revolute)Lever: moves the lever that is motion linked t the first axle
(revolute)Ax1-NoB: moves the rigid group fomed from the second axle and it's cogs
(revolute)Gear-Big/Small1: moves the cogs on the first axle
(cylindrical)Ring: slides on the first axle and rotates with it. 
                has a contact set with the cogs on the first axle that allows it to put them in motion
```

## Powering
The machine powers by spinning the first axle(using the lever

The 3 motion studies show the machine movement in the 3 states neutral, first gear, second gear

## File types in repository
  -.f3d
  -.gif
  -.png
  
## Software Used: Autodesk Fusion 360
