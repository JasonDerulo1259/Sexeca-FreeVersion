
# Sexeca
![Sexeca Banner](https://i.imgur.com/jBlQd4A.png)

Sexeca Is a Bot/Exploit to get the answers on assignments and work on senecalearning.com

**Warning: This Program Was Designed For Educational And Testing Purposes Only. If you use it maliciously or otherwise unacceptably, I will not be held accountable. If you have any legal repercussions from the use of the code or the program, that is your fault entirely and I am not to blame. Furthermore, If anyone wants this program removed, shut down, or anything similar, then please get in contact first and we can discuss it.**

## Installation
(Currently Windows Exclusive) 
There are three methods of download,

Download the unstable version by Clicking the button that says "Code" At the top of the page, and clicking download zip.

Clone the repo using git:
```
$ git clone https://github.com/JasonDerulo1259/Sexeca-FreeVersion/releases
```
Or
[Download the latest zipped file from the Releases tab](https://github.com/JasonDerulo1259/Sexeca-FreeVersion/releases) and extract it into a folder.

Run the Exe file titled "Sexeca.exe"

## Usage
After opening the program, it should come up with a screen like this:
![Image of initial screen - Asking for course ID](https://i.imgur.com/ahw41He.png)

### Course ID and Section ID:
The Course ID and Section ID are what the program uses to find exactly which lesson and section of that lesson you need the answers for. 

You need to find and input these for it to work.

You can find it by going onto your lesson, and copying the two ids from the url
![Pic of url with ids highlighted](https://i.imgur.com/R6OLY0K.png)		
For example, this Url here for GCSE Computer Science
###### app.senecalearning.com/classroom/course/a1ce4570-6e27-11e8-af4b-35cf52f905c2/section/65ac2e24-3b57-4598-b4dc-01e04eddee1b/session
The Course ID would be ```a1ce4570-6e27-11e8-af4b-35cf52f905c2```

The Section ID would be ```65ac2e24-3b57-4598-b4dc-01e04eddee1b```

### Outputs and Errors
After you have put in the course and section ID, It will say something like this (As of the first release)
![Image of output after course+section ID](https://i.imgur.com/S8Lu9mt.png)
If you see this, and not an error message, then it has gone correctly and It should automatically open up.

However, If it doesn't automatically open then you can find the txt document in the folder that the program is in titled "[Name of subject/lesson] Answers.txt"

If you see something like this when it outputs though,
![Image of output after course+section ID](https://i.imgur.com/vtAxVak.png)
Then you have input the course and/or section ID incorrectly and need to restart the program.

If you get a different error message than this, take a screenshot of it and contact me (Links at bottom)
## Free Version VS Paid Version
Alright, so as of right now - the first release - the paid version has not yet been developed so don't worry about that. But the difference between the paid and free version, when it does come out, will be as follows:


|Free version:  |  Paid Version:|
|--|--|
| Batch Processing - NO | Batch Processing - YES |
| Automatically inputs answers - NO | Automatically inputs answers - YES |
| Scheduled Running - NO | Scheduled Running - YES |
| User Interface - NO | User Interface - YES |
| (in the future) Error handling - MAYBE | Error handling on release - YES |
| (in the future) Frequent-ish updates - MAYBE | Frequent updates - YES |

*Obviously, as previously mentioned the paid version has not yet been developed. The README will be updated on release.*
## Output File
The formatting in the text file is displayed at the top of the document, But just incase here it is:

 Sexeca - by JasonDerulo1259
 

Sexeca - by JasonDerulo1259
 
##### Abbreviations:
##### MC - Multiple Choice
##### WF - Word Fill
##### ID - Image Description (formatting is a bit gross but you can figure it out)
##### WW - Wrong Word (for this, see where the "WW starts with" ends and the wrong word will be there)
##### LT - List (there will be an arrow that points to the correct word)
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
## Contact
Feel free to contact me about any issues.

melopelo1259@gmail.com
## License
**Important: Whilst the free version of the software will be on github with a MIT license, The paid version will be hosted elsewhere with a different, more strict license.**

MIT License

Copyright (c) 2021 JasonDerulo1259

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
