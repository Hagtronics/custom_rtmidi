# RtMidi

This is my fork of RtMidi - I have modified the CMakeLists.txt to build a shared library on a Raspberry Pi with only ALSA support.

# Do Not use this fork!!!!! It will not work for you!!!!!
   
instead go to to original at,  
https://github.com/thestk/rtmidi  
  
# Building  
  Start at the Raspbery Pi Home directory,  
  '/Home/pi  
      
  Clone the code,  
  'git clone https://github.com/Hagtronics/custom_rtmidi  
     
  CD to the directory,  
  'CD rtmidi  
    
  Set the permissions on the install script,  
  'chmod +x install_rtmidi.sh   
     
  Run the '''install_rtmidi.sh''' script.    
  RtMidi will be built as a shared library and installed properly on the pi.  
  
# Testing    
  The shared_lib_test directory contains a shared library test project.  
    
## Legal and ethical

The RtMidi license is similar to the MIT License, with the added *feature* that modifications be sent to the developer.  Please see [LICENSE](LICENSE).


