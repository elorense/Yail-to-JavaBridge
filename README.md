Yail-to-JavaBridge
==================
This is a program that will take as input a Yail file (AppInventor's backend language), and translate it into JavaBridge(Java library for writing Android applications).
This was written to include into MIT's (Formerly Google's) web application called AppInventor. AppInventor lets users create Android applications using a visual "blocks" based language.
My main contributions to this project was the parser that is used to parse Yail files, and generate the data-structure used to output the proper translated code.
This can be found in the YailParser.jj file, the classes it generates after compilation, and in AppInventorScreen.java. This was written in JavaCC.

- AppInventorProject.java is the driver class
- Program expects a yail file as input
- Sample Yail file included (molemash.yail)
