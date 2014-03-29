#Jasper Report 
Jasper Report is an open source java reporting engine, is Java based and doesn't have its own expression syntax.

As JasperReports is a Java class library, and is not meant for end users, but rather is targeted towards developers who need to add reporting capabilities to their applications.

##JRXML

JasperReports reports are defined in an XML file format, called JRXML, which can be hand-coded, generated, or designed using a tool ( For this project we will use iReport). The file format is defined by a Document Type Definition (DTD) or XML schema for newer versions, providing limited interoperability.

The main difference between using XML and a .jasper file is that the XML file should be compiled at runtime using the JasperCompileManager class.

#Requirements
1. Windows OS : Windows Vista - 7 - 8
2. Jasper Report IDE i.e: iReport 
3. Tomcat Web Server
4. JDBC 2.0 Driver
5. Java-PDF library

#Installation
To start using iReport, we must first download and install one. Below are the instructions for installing and running iReport in Windows :

1. Open a browser and visit the iReport site at http://jasperforge.org/projects/ireport

2. Click on the download button. It will ask you to register first, but you can skip it.
You should see the following options:

3. Choose the Windows installer.

4. Once the download is finished, install it.

#License
Copyright (C) 2014 Johnny Nassif, CNAM Liban

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
