## Programming Session (May 21)

#### Timings

| Section   | Time       |
| --------- | ---------- |
| Class     | 15 min     |
| Activity  | 20 min     |
| **Total** | **35 min** |

#### Before Starting

*Topics: setting speed separately to each motor, pitch yaw roll, reflected light intensity, building a reliable turn block with yaw*

Offer the challenge assignment for people who feel comfortable with not doing the lesson.

**Challenge Assignment: Make a line follower in 30 minutes**

#### Motor Movement

Why does the negative speed move the robot forward?

360 degrees in one rotation.

Setting speed separately to each motor.

Where `x > 0`

*Ask, how would you move straight?*

`x% x%` moves straight.

 `x% 0%` moves right and `0% x%` moves left.

Turning backwards.

`x% -x%` turns backwards right and `-x% x%` turns backwards left.

#### Brick Rotation Values

What is pitch, yaw, and roll? [Link](https://upload.wikimedia.org/wikipedia/commons/f/fa/6DOF_en.jpg)

*Ask, which do you think is the most useful?*

Yaw is the most useful.

Practical applications for yaw in robotics are moving forward and turning accurately.

#### Color Sensor Values

Don't use the color value because it is very unreliable.

Colors on the mat aren't "pure" colors, they are shades of a color which can be picked up differently.

Reflected light intensity is the amount of light that the color sensor measures.

The darker the color, the more light it absorbs.

*Ask, what could be a practical application for reflected light intensity?*

A practical application for reflected light intensity in robotics is line following.

#### Activity

Make a `MyBlock` to turn the robot. If you finish early, incorporate the yaw value.