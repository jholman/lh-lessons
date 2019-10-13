# LHL-on-Windows : Headless VM

## Introduction

This file attempts to plan and document a strategy for doing the LHL curriculum on a Windows computer.  This is one of multiple approaches I am documenting.

In this approach, we install a VM, but not via vagrant.  We'll need to get SSH and port-forwarding working ourselves.  And then we'll get VSCode to use its swanky `Visual Studio Code Remote - SSH` extension to edit on the VM, and also have a GUI to look at the filesystem if necessary.


### Expected Hurdles

As with any approach where we don't use the sanctioned LHL VM, we'll have to worry about what software needs to be manually set up and configured within the VM.  Postgres, NVM, RVM, who knows.

## Log
