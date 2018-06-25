# STACK Mathematics Questions for Moodle

This is a collection of moodle calculus questions using the STACK plug-in with Moodle versions 3.3+.

## Guide for Ubuntu Linux OS

In order to view and test these questions, we need to do the following:

1. Install `Moodle` following instructions here: 

   https://docs.moodle.org/35/en/Step-by-step_Installation_Guide_for_Ubuntu 
   
   Note: This can be a long and complicated process

2. Install `maxima` on your system, since the STACK plug-in requires `maxima` as the Computer Algebra System (CAS).

   `$ sudo apt-get install maxima`
   
   Note: This installation of `maxima` only functions in the terminal. If a GUI is wished, one can install the `wxmaxima` package.
   
   `$ sudo apt-get install wxmaxima`
   
3. Install `STACK` for Moodle following instructions here: 
 
   https://moodle.org/plugins/qtype_stack

   Run the key health-checks to ensure all components are working well. 
   
   Key functioning features are the CAS and Gnuplot.
   
4. Once `Moodle` and `STACK` are working well, create a course within Moodle and navigate to the local `Question Bank`.

   In the `Question Bank`, find the import option and select the import file type as Moodle `.xml`. Select the `STACK_Export_1_2_3.xml` file to be imported. 

If you wish to implement the entire moodle course, you can backup your created moodle course with the `backup-moodle2-course-3-stacktrial-20180402-0944.mbz` file.

This should provide ample questions to play with! 
