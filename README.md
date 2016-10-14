# RDPWrap
This solution was based on <a href='https://github.com/stascorp/rdpwrap'>rdpwrap</a>, big thanks to stascorp :)

### Building the binaries:
   * x86 Delphi version can be built with Embarcadero RAD Studio 2010
   * x86/x64 C++ version can be built with Microsoft Visual Studio 2013

### Change log:
   * Removed resource module
   * Removed update module
   * Removed license
   * Removed online install mode
   * Added feature to custom dll path and name

### Usage:
    RDPWInst.exe -i dll_full_path   //install rdpwrap module
    RDPWInst.exe -u                 //uninstall rdpwrp module
    RDPWInst.exe -r	                //restart "termservice" service
    
### Attention:
   * The INI file must have the same name as the DLL, and must be in the same directory as the DLL

### Links:
   * rdpwrap GitHub repository:</br>
   https://github.com/stascorp/rdpwrap
