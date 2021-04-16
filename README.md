# emgt-nrj-monitoring

Goal of this project is to show how we can use atoti lib to compute cost and consumption of a complex composed of buildings and appartment and generate appartment invoice automatically.

## Version and changes

### V3 - 15-04-2021 
This V3 is only reading data from csv, and the model have been changed to look like this : 
!(schema V3)[./img/schema-V3-15-04-2021.PNG]

At this stage most of the measures have been created and are working pretty well except : 
 * date_shift which is a known issue : https://github.com/atoti/atoti/issues/263
 
Remaining works : 
* update to new release to see if date_shift measures is working 
* test querying atoti to create a pandas df with all data we need for each appartment and building. 
* test creating a word template and populate it with python , example might come from : https://pbpython.com/python-word-template.html

All data are fake at this point. 
