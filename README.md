## Osiris VM box

The OSIRIS (Open source for IRIS) is an open-source iris recognition system. The original OSIRIS implementation required installing and running ‘OpenCV version 2.4’ and Ubuntu (Linux OS) and does not support more recent versions. These older versions of OpenCV and Ubuntu are preconfigured OSIRIS VirtualBox Virtual Machine.

<a href="https://citer.clarkson.edu/wp-content/uploads/2022/11/OcularCloud_Development_Environment.zip">Download zip file with VMBox here</a>

## Osiris VM box environment

<ul>
<li>OpenCV 2.4.11</li>
<li>Osiris 4.1</li>
<li>Ubuntu Linux 12.04 (Precise)</li>
</ul>

## Installation
Development environment usage has the following minimum requirements

### Hardware

<ul>
<li>Intel Core i5 processor or equivalent with virtualization support</li>
<li>4 GB main memory</li>
<li>20 GB free disk space</li>
</ul>

### Softwar

Oracle Virtualbox version 5 or later

<ul><li>Oracle Virtualbox version 5 or later</li></ul>


## Installation Steps

1. Install <a href="https://www.virtualbox.org/wiki/Downloads" target="_blank">Oracle Virtualbox version 5 or later</a>

2. Download and extract the OcularCloud development environment virtual machine image zip archive

3. Start Virtualbox and create a new virtual machine using the following parameters

<ul>
  <li><b>Name</b>: OcularCloud Development Environment</li>
   <li><b>Type</b>: Linux</li>
   <li><b>Version</b>: Ubuntu (64-bit)</li>
   <li><b>Memory Size</b>: 2048 MB</li>
</ul>

4. When prompted to configure the hard disk, select option Use an existing virtual hard disk file

and select the Osiris virtual hard disk file  {ic_de.vdi}

Click Create.

5. Installation is complete. Within Virtualbox, start the new virtual machine to enter the developer interface.

# Osiris

<a href="https://github.com/5455945/Iris_Osiris"  target="_blank">Osiris</a>

## Documentation 
<a href="https://github.com/ClarksonCITeR/osiris_vmbox/blob/main/Documentation_OSIRIS_v4.1.pdf"  target="_blank">Osiris Documentation</a>


# Licence 

<ul>
  <li><a href="https://github.com/5455945/Iris_Osiris/blob/master/LICENSE"  target="_blank">osiris License</a></li>
  <li><a href="https://ubuntu.com/legal/intellectual-property-policy"  target="_blank">ubuntu License</a></li>
  <li><a href="https://github.com/opencv/opencv/blob/4.4.0/LICENSE"  target="_blank">opencv License</a></li>
</ul>
