# CommonSense (Berend)

CommonSense (created and maintained by TNO) is an application library that facilitates the creation of geo-data web-interfaces. It allows you to display various  types of geo-data on a map and supports filtering and styling of map features.
At the eScience Center we have augmented this with a system that allows a user to start a simulation from the web-interface to run on compute infrastructure. The result of such a simulation can then be displayed again on the map, assuming it is geojson or another supported format.

Things that need work:

- Dissemination: 

There is a short presentation on CommonSense, but it is more than a year old, it needs updating as well as using it to make a pitch presentation. A blog post about common-sense and especially the simulation framework that we made for it would also be very nice.
 
- Documentation:
The current documentation is slightly outdated, so it needs to be reviewed. What would be especially useful is if one or more people that have no prior knowledge of the system use the documentation to integrate their own simulation in the system. This would also result in more examples and/or tutorials.
 

- Tutorials:
There is currently a single example project that actually runs a simulation using this system. To show the strength of the system it would be nice if there were more. The documentation on integrating simulations can also use some examples of how to do certain things.

- Packaging:
Currently the system is a rather intricate set of inter-operating micro-services. The setup has already been simplified by creating a docker-compose project. This project can maybe be simplified and needs more testing on various platforms.

Furthermore it would be nice if we can package the parts that we created for running the simulation in such a way that it can be released as a separate entity (for instance an angular module) as it is currently embedded in a csWeb example website.

There is much more to do, but that is mostly implementation and feature wise which is not the focus of this team-project.
