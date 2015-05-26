An open-source python parser for a file format specification compatible to vmware's vmss/vmsn files.
The file specifications themselves are not yet published, but a sample read-only python parser is readily available.

According to the VMware community: "This[`*`.vmsn] is the snapshot state file, which stores the running state of a virtual machine at the time you take that snapshot"

I took upon myself to create a compatible file type specification(plus a sample parser) in order to extend existing VMWare tools and utilities in an open-sourced manner.