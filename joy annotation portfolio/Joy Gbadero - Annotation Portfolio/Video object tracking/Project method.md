# Project method inferred from the saved work

https://drive.google.com/file/d/1gfWqeOKh5QUEbswsZnJli0MxZ908EdeH/view?usp=drive_link

Project method

Joy Gbadero | Video object tracking | DataLens Africa

## Basis of this explanation

This explanation uses the video, the seven exported tracks, and 108 saved rectangle positions. It separates recorded facts from an inferred working method. It is not the original assignment guide or a record of Joy's private reasoning.

## What the work shows

The video shows moving vehicles with rectangular boxes. Each exported track has one stable identifier and a sequence of timed positions. Position and size change within the tracks. Every saved rectangle has zero rotation.

Seven tracks begin at recorded time 0.04 seconds. T1 and T2 finish with a disabled state. T3 through T7 have final enabled states. Some boxes remain visible after vehicles leave.

## Working method inferred from the project

1. Identify a vehicle to follow and create a distinct track. The separate IDs support this interpretation. The export does not establish a rule to label every visible vehicle.

2. Place an upright rectangle around the vehicle. Saved x, y, width, and height values define each box. The visible examples are consistent with fitting boxes to vehicles.

3. Update the rectangle at selected times as the vehicle changes position and apparent size. The saved sequence supports timed box adjustment, not a claim of manually labelling every frame.

4. Keep the track identity while changing its coordinates. A stable ID is visible in the export. A full check for mistaken identity changes has not been completed.

5. Adjust the box near the image boundary. Several final rectangles lie at the left or bottom edge and become narrower or shorter. This is consistent with following a vehicle out of view.

6. Control track visibility when the object leaves. The two final disabled states show that the project uses this control. Stopping all tracks correctly is an inferred intended rule, not a confirmed result.

The editor displays boxes between saved positions. The separate local replay uses interpolation: it calculates positions between saved points. That rendering step does not prove which editor controls Joy used.

## Working quality criteria

The inferred aims are to follow the same vehicle, keep the box aligned, adjust its size as needed, and stop displaying it after departure. Exact rules for hidden objects, permitted padding, missed objects, and accuracy thresholds remain unknown.

## Vehicle approaching the camera

Recorded: T4 begins with a box width of 4.38% and ends with 15.16% at 13.24 seconds. Its position also changes. These percentages refer to the video width.

Inferred: the box adjustments are consistent with following an approaching vehicle that occupies more of the image. This illustrates changing scale. It does not measure tracking accuracy.

## Vehicle reaching an image edge

Recorded: T2 ends at 1.64 seconds with x approximately 0%, width 5.78%, and enabled set to false. T1 ends at 2.84 seconds with its lower edge approximately 99.72% of image height and enabled set to false.

Inferred: these narrow or shortened edge boxes and disabled states are consistent with ending tracks as vehicles leave. The export does not record Joy's reason for each change.

## A track that remains enabled

Recorded: T3 ends at 3.64 seconds near the left edge, with enabled set to true. T7 ends at 8.84 seconds near the bottom edge with the same state. T4, T5, and T6 also have final enabled states. Later video images show lingering boxes.

Review action: compare each final saved position with the actual departure. If a box continues after its object leaves, correct its ending in the source project and export again. This is a proposed correction, not completed work.

## Different numbers of saved positions

Recorded: T4 has 32 positions. T2 has five. The total across seven tracks is 108.

Inferred: the tracks contain different amounts of saved adjustment. The counts alone cannot establish difficulty, time spent, reviewer feedback, or the number of manual edits.

This account is inferred from the project. It does not reproduce the original assignment rules or claim completed corrections.
