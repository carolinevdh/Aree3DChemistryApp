Aree3DChemistryApp
==================

is a...

PhoneGap iOS app that uses Augmented Reality to render chemical molecules and their reactions in 3D.


More? Sure!

This cross-platform iPad application configures its instance of the modular J2EE framework (see github.com/carolinevdh/Aree) with libraries that can access an SQL database with knowledge about chemical models, and libraries that can reason about these models. It leverages the framework to display and have 3D models of chemical molecules react in an Augmented Reality environment. The framework typically receives an XML descriptor from the client iPad, parses this configuration and dynamically loads the requested libraries, when found on the TomEE server. Once all libraries have been found and chained together, the iPad application uses simple RESTful requests to use its specific configuration on the framework, benefiting from the server's processing power, load balancing and fault tolerance features.

Key technologies used:
PhoneGap, Wikitude SDK (for Augmented Reality), Qualcomm Vuforia (for image recognition), JavaScript, Three.js (for CSS3D), REST

