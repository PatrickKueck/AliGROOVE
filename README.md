# AliGROOVE
As of Perl v5.26, the . in @INC is gone by default. When you compile perl, it implements the default module search path (based on your configure settings) into the binary. @INC search paths can be seen via: perl -V
So with Perl v5.26, there can be some trouble in respect of module identification in the actual AliGROOVE working directory. The actual AliGROOVE v1.07 should be able to identify all necessary module packages (provided with AliGROOVE) in the actual working directory. Otherwise, copying these packages into one of your @INC library paths (represented via: perl -V) would certainly overcome the @INC 'problem'.

New AliGROOVE version (v.107). Older versions cannot deal with IQTree newick strings. This has been solved in v.107. 

Since 2016 GUI versions are no longer supported. 

Follow the AliGROOVE manual instructions.
Compressed GUI version for linux systems is too big for file upload. Please send me an email and I'll send a specific download link.
