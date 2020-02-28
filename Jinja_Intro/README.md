Notes on Jinja
Lead: Christina Holt
2/28/20

Jinja is a tool that you can import in python that helps you to create a template.

To use this tool in our application of running a retro....
    You have a xml template (so a HRRR rocoto, but instead of hard coded paths, new syntax to indicate which parts will change).
    You will put your changes like forecast length and path to obs in a configure file (A .yml will be our choice of configure files).
    You also need a python script that will use your control file and your template and create the final desired xml.


The examples we are reviewing are setup to change namelist items and change which code is running.


The example python script we are looking at 'create_xml.py' can accept a configure file (maybe you have one from a colleague) and command line options (maybe your changes compred to your colleague's experiment).  
Or maybe you are starting from scratch and you pass all arguments to to the python script.  Alternatively, you could try to type out a .yml to serve as your inital config file.  However, this option would require you getting the syntax and names correct so it is likely not as easy as using a script.  
Saving the resulting config .yml will have everything you need to save your expreiment info.
