#README

##1.before run
1. install openni2(x86)
- install the drive or sdk of your depth camera
- install NITE
- install opencv2

##2.configuration in vs2013
1. Configuration Properties，C/C++，Gerenal，在Additiaonal Include Directories项中添加$(OPENNI2_INCLUDE)
2. Configuration Properties，Linker，Gerenal，在Additiaonal Library Directories项中添加$(OPENNI2_LIB)
3. Configuration Properties，Linker，Input，在Additiaonal Dependencies项中添加OpenNI2.lib
4. Go to Project>MyProject Properties and, in Configuration Properties>VC++ Directories...
Added C:\Program Files (x86)\OpenNI2\Redist\; to Executable Directories
5. Added C:\Program Files (x86)\OpenNI2\Include\; to Include Directories
6. Added C:\Program Files (x86)\OpenNI2\Redist\; to Reference Directories
7. Added C:\Program Files (x86)\OpenNI2\Lib\; to Library Directories

##3.run
just run

##4.any question
email:chenxingwangzi@gmail.com