# Cipher Module
### Created by Connor Abdelnoor
#### For an Assessment at Epicodus on: </br> May 22 2015

###Purpose
To build a encryption cypher in PHP and turn it into a custom Drupal module. </br>
Includes: </br>
A custom form with 3 inputs. One input is be a shift value, one is be a direction, and the third is be the phrase to be encrypted. Then a user is redirected to a second page to show the result - the encoded phrase.
</br>
* The shift value is the number of places to shift each letter over.
* The shift direction is direction added to the shift value. For example: "a" with a shift value of 1 and a direction of right would become "b". A shift direction of "left" with a shift value of 1 would turn "b" into "a".
* If the shift amount takes you over the bounds of the alphabet then cycle back to the beginning. For example: a shift value of 3 with the direction of right would turn "z" into "c".



###Drupal Technologies

Custom Modules
* Cipher module created with PHP

###License

The MIT License

Copyright (c) 2015 Connor Abdelnoor

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
