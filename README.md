
Ok, I'm not sure I'm very happy with how this is working.  But,
it's presented here as a working example

I was able to get the "Spark Dev" local IDE to compile both of these
programs.  "FirstProgram" was easy.  It was really just compile and
download.  It's a simple blink a copule of LEDs script.

The ILI9341 was more difficult.  I tried several different things,
but in the end I had to move all of the source code files (from the
libararies) into the "ILI9341" directory.  I then removed any files
that weren't necessary.  After that, I was able to get it to compile
and I was able to upload the firmware through spark.io.


