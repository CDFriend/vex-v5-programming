VEX coding studio is the new development environment (editor) for V5. It's designed to be the successor to ROBOTC.

## What's New?

VCS is very similar to ROBOTC: it provides a text editor, a way of defining the ports on your robot, and a way of uploading your code. It adds a couple of nice new features I really appreciate:

**Windows and Mac Compatibility**

VCS is fully compatible with Windows and Mac - no more freaky Windows virtual environments for Mac Users!

Windows download: https://link.vex.com/downloads/vcs-pc  
Mac Download: https://link.vex.com/downloads/vcs-pc 

**Graphical Robot Setup**

You can now define all your robot's motors and sensors using a graphical interface, not just code! You can still set up your robot using code, but I'll get into that in a later section.

![graphical robot setup](images/getting-started-with-vcs/vcs-graphical-robot-setup.png)

**Switched from C to C++**

With V5, VEX switched the main programming language from C to C++.

C++ is a very complex, powerful language, but don't be intimidated: it's just C with a couple extra concepts added on.

## Starting a Project

When you first start up VEX coding studio, you'll come to a screen like this:

![graphical robot setup](images/getting-started-with-vcs/vcs-first-screen.png)

There are two options for starting a C++ project:

**VEX C++** uses the graphical interface to set up your robot's ports. It might be easier at first, but I think the view gets a little crowded as your robot gets more complicated!

**C++ Pro** uses all text for your project, including the ports configuration. If you're a little bit more confident in your coding skills, I'd highly recommend using this!

## Configuring Your Robot in VEX C++ Mode

When you start your project in VEX C++ mode, you'll be shown an empty screen with a robot brain on it. You can click and drag components onto the screen to use them in your code. 

![robot brain with motors](images/getting-started-with-vcs/vcs-graphical-motors-noports.png)

Note the little `#` symbols beside each motor's name. This means you haven't defined what port the motor goes in! Make sure you add port numbers for **all** of your components, or your code won't compile!

To change the port number for a component, click on the number sign and choose a port on the brain. You can also change the name, which will show up the same way in the code.

![graphical robot setup](images/getting-started-with-vcs/vcs-graphical-motors-selectport.png)

To switch to your project code, click the "text" button in the top-right corner of the screen.

![graphical robot setup](images/getting-started-with-vcs/vcs-text.png)
