at the first many thanks to seife for the Makefile.

# HowTO #

sudo apt-get install autoconf libtool g++ gdb libavformat-dev libswscale-dev libopenthreads-dev libglew-dev freeglut3-dev libcurl4-gnutls-dev libfreetype6-dev libid3tag0-dev libmad0-dev libogg-dev libpng12-dev libgif-dev libjpeg62-dev libvorbis-dev libflac-dev libblkid-dev libgstreamer0.10-dev libgstreamer-plugins-base0.10-dev


## check out makefiles ##
svn checkout http://neutrinohd2.googlecode.com/svn/branches/neutrino-pc neutrinohd2-pc
#  #
cd neutrinohd2-pc
##  ##
# to build neutrino #
make neutrino

# to start neutrino #
make run

# to update neutrino Source Code #
make neutrino-update

# to clean neutrino build #
make neutrino-clean

# to distclean neutrino build #
make neutrino-distclean

# mapped keyboard keys #
ESC = HOME KEY
#  #
F1 = RED KEY
##  ##
F2 = GREEN KEY
##  ##
F3 = YELLOW KEY
##  ##
F4 = BLUE KEY
##  ##
##  ##
F5 = PLAY KEY
##  ##
F6 = STOP KEY
##  ##
F7 = PAUSE KEY
##  ##
F8 = FORWARD KEY
##  ##
F9 = BACKWARD KEY
##  ##
M = MENU KEY
##  ##
- = MUTE KEY
##  ##
RETURN = OK KEY