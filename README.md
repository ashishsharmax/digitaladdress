# Digital-Address-System
The Software is a digital property addressing system which ensures that all locations in the country are addressed. With this software, every location has a unique digital address. The digital address is a composite of the state code plus a plus code (region, district &amp; area code). The software translates your GPS location to a user friendly digital address. With this software, users can now precisely pinpoint any location in India using the digital address of the place. The software will be integrated with Google maps to allow for easy navigation of a particular area, detailing major road networks and other landmarks. 

The software generates a digital address for every valid physical address and correct pincode given by the end user. The digital address consists of a state code and a plus code (area code and local code). The plus code is automatically generated by the Google Plus API. The generated digital address is then stored in the system's database.

## How the code looks like
![zoom](https://user-images.githubusercontent.com/28597524/39563189-bf9e066e-4ecc-11e8-9b4d-10575f1bec9d.gif)

## Code Format
![codemodel](https://user-images.githubusercontent.com/28597524/39563464-f0f28324-4ecd-11e8-910b-ffd66822121b.png "Unique Digital Address Generated")

* First 2 characters of code determines the State
* Next four characters are the area code, describing a region of roughly 100 x 100 kilometers.
* Next four characters are the local code, describing the neighborhood and the building, an area of roughly 14 x 14 meters.
* Last 2 characters further improve the precision of the code upto 3x3 meters.