---
layout: default
title: Dreams
subtitle: Website Design
modal-id: 1
date: 2020-12-29
project-date: None
category: system,virtualisation
description: Lorem ipsum dolor sit amet, usu cu alterum nominavi lobortis. At duo novum diceret. Tantas apeirian vix et, usu sanctus postulant inciderint ut, populo diceret necessitatibus in vim. Cu eum dicam feugiat noluisse.
thumbnail: dreams-thumbnail.png
img: dreams.png
alt: image-alt
client: Start Bootstrap

---





## Independant Virtual Machine, or How to create a VM that can be dual booted



##### Goals

- Having a VM to do tasks on Host and work on guest at the same time, sharing data
- Having the ability to exploit full capabilities of guest OS by booting into it as a full-fledged configuration (dual boot).
  - Using full power of your hardware from the child OS
- 



> ### Why run it natively?
>
> *To play games*. Or to be able to use 100% of the hardware resources for other applications, if you're into productivity and those things... VMs are much more convienent for everything else.
>
> ### Why run a VM?
>
> VMs are super convenient for many reasons:
>
> - They can run side-by-side with macOS without partitioning, rebooting, etc...
> - You don't have to reboot
> - They can be backed up
> - You don't have to reboot
> - You can use snapshots to revert immediately back to working installations
> - You don't have to reboot
> - They can integrate with the host OS for the purposes of transferring files, running guest OS-specific applications, etc...
> - *You don't have to reboot*
>
> Source: http://wheelsandbytes.github.io/comp/vbox-windows/vbox-windows.html



Other goals

- [For programs more hungry in resources.]
- If your computer is slow
  - MacOS is slow. Running a VM will be sluggish
  - Windows will be fast





##### How



- Create a virtual disk that is linked to a physical partition
  - Variations: for an external drive

- 



##### Troubleshooting

Possible issues

- playing with the "Use I/O cache". When I tried using my *internal* drive, it wouldn't work without it.
  Some people in earlier versions of VirtualBox tried needed to disable that option to make things work. You can learn more at [these threads]().

- VERR_ACCESS_DENIED
- 







----------------

A Poll: what do you think of this dataset ?

-[ ] Super helpful! Will share it 😃
-[ ] I would prefer a dataset out of this for analytics or machine learning 📊
-[ ] I would also like to save ad videos by myself. 📹
-[ ] Helpful, but not that much


