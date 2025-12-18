# Electronics and Sensors

A guide on electronics and sensors, and how to incorporate these components to improve the controllability of a robot.

**Coming Soon**

# Sensors

There are several major types of sensors in FRC.

| Type | Use | Common Examples | Image |
|:----:|:---:|:---------------:|:-----:|
| Proximity Switch | Detecting objects and their characteristics | Beam breaks, color sensors |  |
| Distance Sensor | Finding how far away an object is from sensor | Ultrasonic sensors, LIDAR | image |
| Shaft Rotation Sensors | Meauring rotational motion, typically of shafts | Encoders | image |
| Accelerometers | Measuring acceleration to track robot position | Triple-axis accelerometer | image |
| Gyroscopes | Measuring rate of rotation to help track robot heading | Three-axis gyro | image |

## Proximity Switches

Proximity switches are one of the most common sensors in FRC. They have many applications, but mainly they are used for detecting objects, like game pieces. These components, like the name suggests, act as "switches": if a criteria is met (detected by the sensor), then they cause an electrical signal. Switches are divided based on how they are activated, each with their own use case. 

!!! Note

    Some of these sensors may also be known as "limit switches" because they are usually activated when a mechanism hits an endpoint, or "limit." 

### Mechanical Switch

Mechanical switches are the simplest type of switch, being activated by a *mechanical* signal. It is akin to a pressure plate, where applying force causes a signal. Although they work in a pinch and are very simple to use, they come with disadvantages. They can be less reliable and may not work for certain applications. In addition, the switch must be activated mechanically which means an object has to directly press on it, which may not work for certain designs. In addition, since it's sensor is physical, it is susceptible to wear and tear over a season. 

 <figure>
    <img src="" style="width:55%">
    <figcaption></figcaption>
  </figure>

### Magnetic Switch

Magnetic switches are activated when a magnet comes within range of the sensor. These sensors are incredibly versatile due to their simplicity; they are used in many places to detect when a mechanism is at a certain location. Magnetic switches are more reliable than mechanical switches, requiring no contact to activate, and often smaller. However, they require mounting of a magnet in addition to the sensor itself, which is vital to consider when designing with magnetic switches. 

The most common type of magnetic switch used is a "hall effect sensor." This sensor is based on the Hall Effect, which works by converting a magnetic field into voltage. This system results in the creation of a voltage potential, triggering the sensor. Often, the sensor is converted into a digital output. For more information on this topic, visit <a href="https://www.ti.com/document-viewer/lit/html/SSZT164" target="_blank">Texas Instruments' website</a> or watch <a href="https://www.youtube.com/watch?v=wpAA3qeOYiI" target="_blank">this video</a>.

 <figure>
    <img src="/design-handbook/power-transmission/images/" style="width:55%">
    <figcaption></figcaption>
  </figure>

### Inductive Switch

Inductive switches are activated when it senses any type of conductor in a certain range. They are similar to magnetic switches, but are more generalized. Since they can detect any type of conductive metal, they could be a benefit or hindrance. Although not commonly used in FRC, they may be helpful for specific cases. For more information, visit <a href="https://www.baumer.com/us/en/service-support/function-principle/working-principle-and-technology-of-inductive-sensors/a/Know-how_Function_Inductive-sensors" target="_blank">this website</a> to understand how they work and their applications/use cases. 

<figure>
    <img src="/design-handbook/power-transmission/images/" style="width:55%">
    <figcaption></figcaption>
</figure>

### Photoelectric Switch

Photoelectric switches are able to detect objects by reflection light (usually an IR laser) off them and detecting if the light crosses a threshold. Like other no-contact sensors, it is very versatile and can be easier to use. However, certain types of sensors can be unreliable due to ambient competition light affecting their performance. 

Often, these switches act as beam breaks with two components: a transmitter and a receiver. The transmitter sends a laser to the receiver, sitting opposite each other. When this beam is broken, the sensor is activated. This can be very useful for detecting when a game piece passes a certain point in the robot or for detecting other objects.

### Time-of-flight Switch

## Distance Sensors

## Encoders

## Accelerometers and Gyroscopes

# Electronics

There are a vast amount of electronics available in FRC. As a designer, it is important to design for these electronics and understand how to mount them. 

# Cameras

<br>