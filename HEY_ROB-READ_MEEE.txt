for this to work, you need to move a copy of baxter_description into the examples folder or something, and I probably renamed it so it wouldn't kill all the rest of the files in the party ws

Also, on 7/7/14, you copied a version to a new ws (~/ws/newdev), to overlay the original party ws so you could modify baxter_common, etc. on top of the others...
To address this resource loading problem, I'm creating a folder in examples with sym links to any necessary ROS packages.
