# midi4l

midi4l is a Max object that brings full MIDI support to M4L (Max for Live). 
It allows you to access MIDI input and output ports inside Max for Live with support for MIDI channels, polyphonic aftertouch, and SysEx messages.

midi4l is developed in cross-platform native C++ code and has no runtime dependencies. To use, simply add the compiled object and patches to
your Max file search path.


## Building from Source:

1. Get the Max SDK from https://cycling74.com/downloads/sdk/ (this was developed against the Max 6.1.4 version of the SDK)
2. Checkout this git repository under the SDK examples folder
3. Open the Xcode or Visual Studio project in the src folder
4. Build


## Code Dependencies (included in this project)

MaxCpp: https://github.com/grrrwaaa/maxcpp   
RtMidi: http://www.music.mcgill.ca/~gary/rtmidi/   
See the source files for these dependencies in this project for license info.


## License

Copyright (c) 2014 Adam Murray and James Westfall   
https://github.com/adamjmurray   
https://github.com/aumhaa   

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
