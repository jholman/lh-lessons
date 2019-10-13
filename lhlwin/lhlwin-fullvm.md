# LHL-on-Windows : Fullscreen VM

## Introduction

This file attempts to plan and document a strategy for doing the LHL curriculum on a Windows computer.  This is one of multiple approaches I am documenting.

In this approach, we install a VM, but not via vagrant.  In particular, a headed VM with a desktop environment.  Then, to do any work, we simply load the VM in fullscreen, and do everything inside the VM.

### Expected Hurdles

As with any approach where we don't use the sanctioned LHL VM, we'll have to worry about what software needs to be manually set up and configured within the VM.  Postgres, NVM, RVM, who knows.

Also, if someone wants to portforward so that their in-VM software can be seen from other computers, that'll be an extra step

## Log
