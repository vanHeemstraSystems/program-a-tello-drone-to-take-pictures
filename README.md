program-a-tello-drone-to-take-pictures
# Program a Tello drone to take Pictures

Based on "Program a Tello drone to take pictures and then classify the images" at https://developer.ibm.com/tutorials/program-ryze-dji-tello-drone-using-sdks-and-node-red/

Use the Ryze and DJI SDKs to control their Tello drone API with Node-RED and Watson Visual Recognition nodes.

In this tutorial, we present the high-level steps from our workshop where we show you how to program a [Ryze DJI Tello Drone](https://www.ryzerobotics.com/tello) by using the Ryze and DJI APIs in their SDKs and Node-RED. Join the open source community, like in the [TelloPilots forums](https://tellopilots.com/), and learn how to program the Tello.

## Prerequisites
To classify the pictures that your drone takes, you’ll need to create a Watson Visual Recognition service instance in IBM Cloud. So, you’ll need to create an [IBM Cloud account](https://cloud.ibm.com/registration?cm_sp=ibmdev-_-developer-tutorials-_-cloudreg).

You need to have experience using [Node-RED](https://developer.ibm.com/blogs/open-source-ibm-node-red-low-code-visual-development-tool/), which is an open source, low-code visual programming environment.

To control the drone, you need to connect your computer to the drone wifi access point. So, you need to [install and run Node-RED locally](https://github.com/johnwalicki/Node-RED-Tello-Control/blob/master/docs/PART2.md), rather than in the cloud.

After you’ve installed Node-RED, you need to [install several additional nodes](https://github.com/johnwalicki/Node-RED-Tello-Control/blob/master/docs/PART2.md) that we will use in this tutorial.

**Remember:** Be careful when when you fly your drone. Fly your drone indoors at your own risk. Also, be respectful of your neighbors and public property when flying your drone outdoors. When you record video and take pictures with your drone, be mindful of other people’s privacy. Obey all FAA regulatory restrictions posted about UAV flight prohibitions.

