swing-desktopScrollPane
=======================

A scroll pane that knows how to add scroll bars to a swing JDesktopPane component.


For a long time there has been a known issue with Swing's JDesktopPane. If a JInternalFrame gets out of the view port, 
no scrollbars are added and you loose the ability to "reach" the JInternalFrame.

This component ainms to fix that issue. You simply pass it a JDesktopPane and add it to a app instead of adding the 
JDesktopPane.

This component will keep track of JInternalFrames position and add scrollbars when it's appropriate.

