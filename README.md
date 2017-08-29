## Instructions on compiling
### Preperation
  1. Download the ZIP from github.
-----------------------------------
### Installing dependencies:-
  **On Linux**:-
  ```
  sudo apt-get build-essential cmake libboost1.55-all-dev
  ```
  **On Mac**:-
  
  **Installing HomeBrew**:-
  

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

    
  **Installing dependencies**:-
  
    brew install cmake
    
    and then 

    brew install boost

    
  **On Windows**:-
  **Installing CMake**:-
  
    Download the CMake binaries from this [link](https://cmake.org/download). Choose the windows installer.
    
  **Installing Boost**:-
    Download Boost from this [link](www.boost.org/users/download/). Choose 'Windows binaries' under 'Third Party Downloads.'
    
-------------------------------
### Compiling
  **On Linux**
    1. cd into the directory in which you have downloaded the zip.
    2. unzip it using this command 
    ```
    tar xvf master.zip
    ```
    3. cd into the unzipped directory
    4. Run make:-
    ```
    make -j [no. of threads]
    ```
    5. The binaries can be found under 'flericoin-master\build\release\src'
  
  **On Mac**
  
    1. Open up your downloads folder (or wherever you downloaded the zip)
    
    2. Unzip the file
    
    3. Open Terminal under '/Applications/Utilities/Terminal.app'
    
    4. cd into the directory that was extracted 
    ```
    cd [directory]
    ```
    5. Run make:-
    ```
    make -j [no. of threads]
    ```
    6. The executables can be found under '\flericoin-master\build\release\src'
  
  **On Windows**
  
    1. Unzip the downloaded file.
    
    2. Open CMake.
    
    3. Under 'Where is the source code' choose the unzipped folder.
   
    4. Under 'Where to build the binaries' choose the folder in which you want the exectubales to be built.
    
    5. Hit 'Configure,' and then 'Generate.'
