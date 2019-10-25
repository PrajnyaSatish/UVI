This file contains suggestions we may need to pay attention to when maintaining UVI. If you have any ideas or make any changes, please wirte them in this file.

(1) Sense keys and framenet mappings have been added to all the VerbNet classes. Make sure before you change anything in the svn to run 'svn up' and get the latest version. Whenever members are moved, make sure to keep their sense key and fn mapping the same. Whenever a member is added, find the highest sense key for that verb, and just add one to make a new sense key! Deleting members should be fine - we don't need the sense keys to be strictly ordered in any way. 

(2) Changes are being made to migrate from 2 different search files(search.html and uvi_search.html) to a single one (uvi_search.html). 
