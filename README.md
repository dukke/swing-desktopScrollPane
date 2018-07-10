swing-desktopScrollPane
=======================

A scroll pane that knows how to add scroll bars to a swing JDesktopPane component.


For a long time there has been a known issue with Swing's JDesktopPane. If a JInternalFrame gets out of the view port, 
no scrollbars are added and you loose the ability to "reach" the JInternalFrame.

This component aims to fix that issue. You simply pass it a JDesktopPane and add it to a app instead of adding the 
JDesktopPane.

This component will keep track of JInternalFrames position and add scrollbars when it's appropriate.


# About The Author
I hope you don't mind just a bit of publicity. I'm a [JavaFX and Swing Freelancer and Consultant](https://www.pixelduke.com),
but more generally can be described as a Front End Freelancer and Consultant since I also have experience in web technologies,
building web apps, etc, and have experience in User Interface Design and User Experience. If you need professional assistance 
feel free to [contact me](https://www.pixelduke.com/contact).  
Still this is, and will remain being, a free and open source library, so feel free to use it, royalty free, in your projects commercial or not.
