
-- Starting your MSc:

Discuss with Professor Jose Gaspar the creation of a working repository


-- Create an MSc folder in your PC (suggestions for Windows OS):

mkdir c:\msc
mkdir c:\msc\GIT
mkdir c:\msc\matlab.my

Install TortoiseGIT and "checkout" your repository into c:\msc\GIT\.
(See next how to install "matlab.my")

Your GIT contains default folders:
c:\msc\GIT\refs		folder containing papers and other references (PDF)
c:\msc\GIT\sw		folder to contain software packages, others and yours
c:\msc\GIT\sw_tst	tests and experiments based on the sw packages
c:\msc\GIT\data		datasets to use


-- Download and install Matlab utils on your PC (folder "matlab.my")

See install details in:
http://users.isr.ist.utl.pt/~jag/software/matlab_my.htm
https://web.tecnico.ulisboa.pt/ist13495/software/matlab_my.htm

Function "addpathx.m" gets available after installing "matlab.my".
In Matlab, goto to the "matlab.my" root folder and type:
	>> mtlmyini( 'install' )

You can install also "matlab.extras". It is recomended but not mandatory.

After installing "matlab.my" you can install more mcode folders:
	>> mtlmyini( 'install_this_folder' )
which places information into "matlab.my\mtlmyini_path.m".

