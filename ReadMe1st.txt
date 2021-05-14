Richard,
      This is an development version of the safe-guard module, it sits in the background not appearing to do much. If a known virus is found it'll tell you (but do nothing about it yet). As far as I know it works invisibly with everything (Ive now fixed the bug with CC apps) . Its also spots a lot more viruses than Vprotect :-)


Things it does do
~~~~~~~~~~~~~~~~~

Check all obey files for known infects (just string-compare)
check for invisible wimp task, as used by Icon varients (RO3 only for now)
Check all module & absolute for known appending-viruses
Checks all modules / sprite files to see if they are valid
Check for odd things that give individual viruses away

Things that will be in the next version (real-soon-now)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*checkboot will turn the checking of boot files off/on, this will reduce the number of viruses found very slightly, but will speed up the checking procedure a lot.

A look up table for viruses name, in the majority of cases you will get the virus reffered to as 'A VIRUS'

Check basic files to see if there are valid

An improved set of docs. SGDocs is just for my own refference at the mo. I'll turn it into something more useful soon.

An option to set how often the wimp_checking routine runs (set to 20secs at the mo)

... and of course It needs a hell of a lot of testing, It runs invisible on my A3000, but it not been tested on -anything- else, it -will- run on RiscOS 2, but some of the features wont work. I'll try to patch them for RO2 for the next version

I appreciate any comments you have on it, expect the next version in a week or so (along with the media-checking app with is coming along very-fast). If possible could you send me a copy of Investigator III, for my app can have a similar look and feel.

Cheers


Glenn
