Momo
=====================
A tiny JCR (Java Content Repository) browser in Swing.

Current build status: [![Build Status](https://buildhive.cloudbees.com/job/decebals/job/momo/badge/icon)](https://buildhive.cloudbees.com/job/decebals/job/momo/)

Features/Benefits
-------------------
Momo is an open source (Apache license) tiny JCR Browser.   
With Momo you can browse a JCR, you can view the item's properties. Momo comes with built-in viewers for images and xml files.    
All you must to do is to set some properties in the momo.properties file.  

How to use
-------------------

`mvn clean package`
`mkdir dist`
`cd dist`
`copy ../target/momo-*.zip .`
`unzip momo-*.zip`
`java -jar momo-*.jar`

DON'T FORGET
You must create a file momo.properties from momo.properties.sample.

License
--------------
Copyright 2013 Decebal Suiu
 
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with
the License. You may obtain a copy of the License in the LICENSE file, or at:
 
http://www.apache.org/licenses/LICENSE-2.0
 
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on
an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.
