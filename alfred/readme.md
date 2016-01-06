Some random alfred workflows, downloaded from the interwebs, some customized.

Network:
    ipi - show internal ip
    ipe - show external ip
    ifs - show up interfaces
    ping <host> - pings and copies to clipboard
    nslookup <host> - and copies ip to clipboard

System:
    top to show top processes, m or c flag is also ok

Files:
    f to search paths in home folder (simple folders filter)
        press cmd + down to browse folder;
        press shift to quicklook
        press right arrow to show possible actions over file
        https://github.com/zhaocai/alfred2-top-workflow

subl to open folder in sublime

Conversions:
    conv 100 usd eur

Dash:
    ex. akka
    search using installed docsets. Requires dash

Recent files:
    r

timer:
    timer 5s <msg>

Stack overflow:
    .so <query>

Finder/Terminal:
    ft - open current finder in terminal

Scratchpad:
        After you set a hotkey, you can select text and edit it on the Alfred command line. When you press enter, it will be placed into the clipboard.
        If you press <cmd> and enter, it will place it into the clipboard and the top most application.and this
        If you press <ctrl> and enter, the text will be preppended (changed from appended) to the end of a selected text file.
        If you invoke the keyword “sp:” or if you press the hotkey without a selection, it will offer to put the clipboard as the text to edit. Press enter on the “clipboard” option and the contents of the clipboard will be copied to the Alfred command line for editing.
        Cmd + shift + s to directly open the scratchpad file (created the path ~/scratchpad/scratchpad.txt) and set file as scratchpad. It uses mvim and a custom profile: /usr/local/bin/mvim -u ~/.vimrc.distractionfree -- ~/scratchpad/scratchpad.txt
