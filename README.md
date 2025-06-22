# Teknofest 2025 VSign ML&AI department

This is a pipeline for converting English text into American Sign Language(ASL).

It consists of 2 parts:

* Text_to_ASL gloss model: Converts English text into ASL gloss
* ASL_to_Avatar: Maps ASL gloss to their corresponding pose

## Pipeline Overview

English Text --> [Text_to_ASL Gloss Model] --> ASL Gloss --> [ASL_to_Avatar Model] --> 3D Avatar Pose
