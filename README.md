# ME 701 -- Homework 1 -- Your Name Here

## Instructions

Your solution should be an update to this `README.md` file that will be
committed back to your repository created when you clicked the HW 1 link.

## Problem 1 -- Open-Source Software

### Statement

Think of the things you do routinely on a computer that require
specific software packages.  Find an
open-source solution from the software repository
for one of these activities and tell me about it in 100 words or less.
For example, I used to do lots of audio recording when I was in
high school (not *that* long ago) and used special (and
pretty expensive) tools like
Cakewalk Sonar.  Since then, I've found an
open-source package for doing multitrack
recording called Ardour that doesn't have all the bells and
whistles but, because I can program in C++ and the
source code is available, I could, in theory,
create any such whistles I need.  **Note**: You may not
describe anything already discussed in class (e.g., the LibreOffice suite
or Octave).

### Solution

As an avid PC gamer, I often find difficulties organizing all my installed games
in one place. With multiple launchers (Steam, EPIC Games, Xbox Gamepass, etc) it can
be difficult to truly know what games I have. The open source solution I found was
a Video Game library manager called Playnite. With Playnite, I can view all my games,
both official and emulated, in one clean location. If I ever feel the software could
benefit from an additional feature (say, adding custom tags to organize games), I 
could easily add said feature using my coding knowledge.

## Problem 3 -- Your CPU

### Statement

Figure out how to display information about your CPU via the
command line.  This should include at least the **processor
speed** and the **number of cores**.  Describe your command(s) below.
(Hint: redirection is helpful; remember, that's like
using `ls > directory_contents.txt` to dump the contents of a directory to a file.

### Solution

To display CPU information, I used the following command:

```bash
lscpu # Displays a variety of info, including number of cores
	# and processor speed in Hz
```

## Problem 4 -- Resource Hogs

### Statement

Figure out how to list the programs that use the most
amount of (1) processing and (2) memory.  Describe your command(s)
in your writeup.

### Solution

'''bash
top	# The top command displays various imformation about current processes.
	# Both the processing amount and %memory are given.
'''

## Problem 5 -- `bash`

### Statement

Where is `bash` located on your Linux system?  And what version of
`bash` are you using?  Make sure to provide any commands you use to
determine this information.

### Solution

bash is located within the main bin directory, found using the following commands:

cd /bin # Opens the bin directory, where bash is located
