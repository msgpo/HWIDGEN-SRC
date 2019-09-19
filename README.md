# HWIDGEN Souce Code

This project provides the source code of the popular HWIDGEN Windows activation "tool" which basically is an AutoHotKey script compiled as .exe binary. 


## Discussion
A public discussion around the source code can be found [here](https://old.reddit.com/r/Piracy/comments/d654al/contribution_hwidgen_source_code/). 

The official developer provides support for his tool at Nsane (hidden)/[AiOwares forums](https://www.aiowares.com/showthread.php?tid=246) (read-only). A public hwidgen mirror can be found [here](https://old.reddit.com/r/sjain_guides/comments/9qyuij/hwidkms38genmk6_download_and_usage_guide/), an unofficial support thread is avbl. over [here](https://www.reddit.com/r/sjain_guides/comments/aviidg/support_thread_2_ask_questions_here/).


## Contributing
* Do not abuse GitHub's issue ticket for any basic discussion, otherwise I'm going to close it!
* Constructive feedback is welcome.


## Credits
* The main credit goes to the original author of HWIDGEN - slave (aka s1ave77). 
* All contributors for this project which helped to reveal the source code or to provide some useful background information, pull requests. 
* The people (including me) which originally worked on the first 'KMS solution'. KMS Pico was not the original project, but got very popular because it got published on a bigger russian website.
* avxgov which contributed (a lot) to the original HWIDGEN project.
* Cynecx for the SECO Injector.


## License
This project has no real license (unlicensed) since I'm not the original developer of "HWIDGEN". HWIDGEN-SRC only provides the information and the files to show how the script works and how Microsoft license verification is been bypassed.


## Project Goal
* Opening and realasing the full source code of HWIDGEN.
* Provide an archive/changelog.
* Provide a full documentation on how HWIDGEN really works.
* Provide compiler & decompiler instructions.
* List & show external dependencies which are required by HWIDGEN.


## Dependencies
HWIDGEN requires several dependencies to run:
* Windows 10
* gatherosstate (can be extracted from the Windows 10 Image)
* slc
* AutoHotKey ("compiler")


## Why isn't the original HWIDGEN tool open source'd?

**Notice:** - The strange part is that slave releases his source for his other tools on [GitLab](https://gitlab.com/s1ave77). - 

There are multiple reasons, the original author slave has another opinion on open sourcing programs than I have. He believes keeping the source closed will prevent people from stealing his work. Keep in mind that I do not stole his work here, I just provide the code because refused it (many times) to open and he got several times asked (e.g. on Reddit, Nsane,..) to realease it, yet he (still) refuses to do that, so let's decompile it and show the world how his script works. 

### Personal comment
I believe publishing the source code is overall a good thing for everyone because it levels the playing field. White hats, "cracker" or other people want to know about the current Windows activation holes and I don''t think that ["security through obscurity"](https://en.wikipedia.org/wiki/Security_through_obscurity) is the way to go. Most people simply want to learn from Windows exploits/holes. It also helps to find new strategies and holes in case Microsoft modifies/patches something.

Several attempts have been made to open source (fork) hwidgen, e.g. [DigitalLicense](https://github.com/ARAlex143/activator) script.


## Isn't it dangerous to open source it, now Microsoft can learn from it and close the hole!
* Microsoft certainly has some anti-piracy measures in place e.g. Windows Home Server never got cracked (there is only a trial reset), so if Microsoft really wants to shutdown something or prevent someone from activating the OS they "could" - no matter if the activation program is closed or open sourced!
* Microsoft makes (similar like Intel) most money with Server Hardware/OS, not the desktop consumer market, that does not mean they don't care about "the little ones" but the priorities are just different. 
* Microsoft is already well aware of all activation "tricks", most source is already on GitHub, GitLab & Co. Some (old) holes like KMS simply can't be easily shutdown without _hurting the OEM customers_.

