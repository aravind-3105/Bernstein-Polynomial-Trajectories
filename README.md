# Robotics: Planning & Navigation: Assignment 2A

This half of the assignment is designed to get you familiar with fitting Bernstein polynomials to non-holonomic robot trajectories.
You are also required to answer the questions mentioned in the [Assignment PDF](/Assignment2.pdf) through experiments. The current deadline is for only this half of the assignment. The second part will be released after the submission of the current half, and you will be required to use the code and observations from this part to complete it.

## Instructions:

* Submit your code files and a report in the GitHub classroom repository. Do not upload the simulation videos to the assignment repository.

* Provide the OneDrive/Google Drive links to the generated simulation videos in the report or in the repository README.

* For stitching simulation images into videos:

In `mkmovie.sh` enter the path to the directory where the snapshots are stored and edit the name of the simulation. For example, if my simulation screenshots are stored in the directory `nonhn_tree/`, I will run the following command:

`ffmpeg -r 2 -f image2 -i nonhn_tree/snap%d.png -s 1000x1000 -pix_fmt yuv420p -y simulation.mp4`


### Deadline: 

**March 31, 2022, 11:55pm**


# Videos Link: https://iiitaphyd-my.sharepoint.com/:f:/g/personal/aravind_narayanan_students_iiit_ac_in/Eu3xQyMHT5FKtLm1d_Z8An8BwizjHAcC8OzbLc1FQEDNWA?e=n4L9lv
