# CC16prj

GitHub  for sharing elements of my DSU CodeSchool 2016 Project
Some of the code here is reproduced under BSD attribution licenses
Please do not remove the related  notices  where they appear in  source.

This project Uses a  wide  varity of  technologies,  and maybe not always in the most  appropriate  way.   The  primary  goal  was  to demonstrate  a  working application framework  using the technologies we reviewed/practived  during  our  6 weeks  of  instruction.

These  technologies  included

HTML
CSS
JavaScript
JQuery
React
npm
NodeJS
MongoDB

For personal reasons,  there  were  additional  design  considerations.
Instead of  focusing on implementing  cross-browser compliant code,  I implemented my application  in  QT.  Version  5.7 of  QT  offers the  opportunity to write once and install on all modern platforms.  The  web browswer functionality is  supported in QT by the  webEngine "widget".
The  QT  webengine  is  a  semi current release of the  GOOGLE(tm)  Chromium  platform, providing  native  support  for  all our  target  technologies.

Most importantly,  QT  offers  support   for inter-process  communication between the  C++ native application  and the  webEngine HTML/CSS/JavaScript stack.   This  Interprocess communication technique  is demonstrated by the  example  program  which forms the  basis of this  projects  first  commits


 
