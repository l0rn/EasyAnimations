# MotionLayout animated header with scrollable content below

This repository serves to point out a but in MotionLayout (constraintlayout:2.0.0-beta4) which allows you to leave the motion to be stuck in in between.

The bug only occurs when using constraintlayout with appcompat 1.1.0 but not with appcompat 1.0.0. This is easily verifyable by changing the appcompat version of this project.

[Click for a video of the faulty behavior](bug.mp4)