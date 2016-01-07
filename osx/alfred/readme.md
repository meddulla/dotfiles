## Alfred workflows

Some random alfred workflows, downloaded from the interwebs, some customized.

### Network
src: http://www.packal.org/workflow/network-tools (added ipi, ipe and ifs command)
* ipi - show internal ip 
* ipe - show external ip 
* ifs - show up interfaces 
* ping - pings and copies to clipboard nslookup - and copies ip to clipboard
* nslookup - looks up a host and copies the ip to the clipboard

### System
* top to show top processes, m or c flag is also ok (https://github.com/zhaocai/alfred2-top-workflow)

### Files
* f to search paths in home folder (simple folders filter); press cmd + down to browse folder; press shift to quicklook press right arrow to show possible actions over file https://github.com/zhaocai/alfred2-top-workflow
* Recent files: r
* Finder/Terminal: ft - open current finder in terminal

### Applications
* Sublime text: subl to open folder in sublime; adds open with option (https://github.com/franzheidl/alfred-workflows/tree/master/open-with-sublime-text)
* Dash: ex. akka search using installed docsets.

### Misc
* Conversions for several units, eg. conv 100 usd eur (https://github.com/deanishe/alfred-convert)
* Timer, eg timer 5s wakeup! (http://www.packal.org/workflow/simple-timer)
* Stack overflow: .so (https://github.com/deanishe/alfred-stackoverflow)

##### Scratchpad 
Requires that the path ~/scratchpad/scratchpad.txt exists.

Press hotkey cmd + shift + s with text selected and text can be edited on the command line. Then:
* Press enter - text will go the clipboard
* Press <cmd> and enter - text will go into the clipboard and the top most application.and this
* Press <ctrl> and enter - the text will be prepended (customized from appended) to the end of a selected text file.

Write "sp:" or if you press the hotkey without a selection, it will offer to put the clipboard as the text to edit.

Cmd + shift + s to directly open the scratchpad file. It uses mvim and a custom profile: /usr/local/bin/mvim -u ~/.vimrc.distractionfree -- ~/scratchpad/scratchpad.txt
