DIY MacBook Photo Booth

This workflow:

1. Prompts the guest to enter their name
2. Creates a folder specific to that guest in a 'CurblyPhotoboothPictures' folder in your Pictures folder ("~/Pictures/CurblyPhotoboothPictures")
3. Snaps three photos using the computer's built-in camera
4. Saves the photos to the guest's folder (individually)
5. Combines the three photos into a vertical strip
6. Prints the strip


Requirements:

- Mac computer running OS X 10.6.4 (Snow Leopard) or later, with a built-in or attached iSight camera
- Inkject printer and sheets of 4x6 photo paper


Printing:

The application assumes you're printing on 4x6 photo paper inserted horizontally into a standard printer. In other words, you should insert your 4x6 photo paper into your printer like this:


 				6in
			--------------------------------|
			|				|  |
			|				|  |
			|				|  |
4in			|				|  |
   			|				|  |
   			|				|  |
   			|				|  |
			--------------------------------|  |	<-- bottom right corner of manual feed tray
-----------------------------------------------------------|

				Paper feed direction
					|
					|
					|
					V


SUGGESTION: Try the application once through with normal, 8.5x11" paper in the manual paper feed tray to see how the strip prints out, then insert your 4x6 paper accordingly.


!!!GOTCHA!!!

If the application compains about the New PDF Contact Sheet step failing, try copying the 'New PDF contact sheet.action' file from the 'resources' folder into 'System > Library > Automator'.



CHANGELOG:

2/16/16 - Updated to work with OS 10.11.1 El Capitan





License:

This software is distributed under the MIT license.

The MIT license:
Copyright (c) 201-2016 Curbly, LLC

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
