# ue4-perforce

Finding a comprehensive perforce typemap and p4ignore for Unreal Engine 4 games was a pain so I'm sharing what we came up with.

This configuration is for a source built version of UE4 with an included Project

This setup allows both Mac and PC to compile builds without checking anything out from perforce.

In .p4ignore and P4-ReconcileNewBinaries.bat change GAMEPROJECT to be your project's folder.

ReconcileNewBinaries adds any updated binaries for Windows to the changelist so you can push it to Perforce for your designers.

I'm sure this setup isn't perfect so please let me know if it can be improved!
