
.. Introduction to Virtualization slides file, created by
   hieroglyph-quickstart on Mon Dec 15 21:52:38 2014.

.. Copyright 2015 Donovan Finch

.. Licensed under the Apache License, Version 2.0 (the "License");
.. you may not use this file except in compliance with the License.
.. You may obtain a copy of the License at

..    http://www.apache.org/licenses/LICENSE-2.0

.. Unless required by applicable law or agreed to in writing, software
.. distributed under the License is distributed on an "AS IS" BASIS,
.. WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
.. See the License for the specific language governing permissions and
.. limitations under the License.


Introduction to Virtualization
==============================

'I herd U liked computers, so I put a computer in your computer so you can compute while you compute'


Virtualization
==============

* Virtualization is a word with many meanings.
* The type covered here is 'to run one computer (Operating System and software) inside another'
* Gives additional control and options that may not be available on the 'inner' OS


Uses
====

* Learning - OSes, configurations, software
* Testing
* Security Separation - keeping separate what could run together
* Multiplexing - running together (on the same physical hardware) what cannot be run together (on the same OS, etc)


Technologies - Backend
======================

The backend, or hypervisor, performs the virtualization. It creates and connects the various virtual hardware assigned to the virtual machine when it is started, runs the machine, and disconnects and destroys the virtual hardware when the machine is stopped.

.. nextslide::

:Small Scale:

* Virtualbox
* VMware Workstation (Windows/Linux) & Fusion (Mac)
* QEMU/KVM
* Xen

.. nextslide::

:Large Scale:

* VMware ESXi
* QEMU/KVM
* Xen
* OpenStack Nova


Technologies - Frontend
=======================

The frontend is whatever method the user has of interacting with the virtual machine.

.. nextslide::

:Small Scale:

* VirtualBox
* VMware Client
* Vagrant
   - Universal CLI Frontend
* Libvirt (QEMU/KVM, Xen)
   - virsh CLI
   - VMM (Virtual Machine Manager) GUI
   - Universal CLI & GUI interface

.. nextslide::

:Large Scale:

* VMware vSphere Client/Web
* Ganeti (KVM)
* Xen Orchestra
* OpenStack Horizon
   - Universal Web Frontend
