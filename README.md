# Nintendo Switch Binary loader for IDA Pro 7.0 (NRO, MOD, NSO)

This is a loader for the NRO Nintendo Switch binaries

It's still work in progress but it looks good so far ;)

# Installation

Copy Switch64.dll to "IDA 7\loaders"


# Changelog

v0.1 Initial release

v0.2 Fixed base address(String refs. work now)

v0.3 Fixed segment offsets

v0.4 Support for dumped MOD0 files 

      Dump the sections (RX, R, RW) and merge them into one file to use it in IDA
		
      Parsing of exported symbols

      Parsing of imported symbols (Not sure if it's right)                 


v0.7 Support for NSO files

	Improved parsing of symbols
	
	Small fixes
	
	Support for AArch64 decompiler
