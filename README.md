# Visual/CSS Regression Testing Research

# Reference Guide(s)
    - Gulp Repo for BackstopJS - https://gitlab.com/edgar971/BackstopJS


#Installtion Steps:
-------------------

// Initial steps into installing BackstopJS.
// This should create a node_modules folder within the root folder
1. Within the project (root) run *npm install backstopjs* in GitBash or CMD.

// Installing genConfig - This allows BackstopJS to generate config files.
// Installing inside backstopjs folder - ./node_modules/backstopjs
2. run *npm run genConfig*
    - '/backstop_data' folder is created in the project root.
    - '/backstop.json' file is created in the project root.

// Generating reference screenshots to start regression testing
// Captures script from every breakpoint listed in the ./backstopjs.json file.
// Image captures will now be stored in - ./backstop_data/bitmaps_reference
3.  From the same directory (./node_modules/backstopjs) - *npm run reference*

// Running regression test based off earlier reference screeshot (step 3)
// When you run the test command for the first time a 'bitmaps_test' folder is created.
4. Run *npm run test* - once test is completed your browser should open with regression report.


