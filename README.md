 Ansible Linux Desktop Setup
==========================
This ansible playbook collection creates [L3D](https://chaos.social/@l3d)s Desktop enviroment. Including window manager and some pre-installed programms like [Firefox](https://www.mozilla.org/de/firefox/new/) and some usefull shell programms.

 What is happening here exactly?
--------------------------------
For a complete overview please have a look at the ``README.md`` Files from each ansible role.

*alphabetical Order*
 + akku-warning:
   - monitor akku charging in the background via cronjob
   - create a popup if the akku is under 25%
 + arch-fonts:
   - will install some fonts, if you are using arch linux
 + authorized_keys:
   - Manage SSH Public Keys, Users and authorisation
 + dotfiles:
   - Create some dotfiles like .vimrc and .bashrc
 + i3wm:
   - install and configure i3 window manager
 + install-firefox:
   - Install firefox including some plugins - if you are using arch
 + networkmanager:
   - install NetworkManager including some requirements
 + nextcloud:
   - install nextcloud-client (on arch)
 + no-sleep:
   - didable suspend and screen saver
   - install lock after time (optional)
 + ntp:
   - it is about time!
 + openvpn:
   - install some requirements to use openvpn
 + pulseaudio
   - install pulseaudio with some requirements
 + steam:
   - install steam client (incomplete)
 + winehq:
   - install wine
 + workstation_paclages:
   - install some office packages
   - install some terminal packages
 + xrandr:
   - install xrandr and arandr

 Install tipps:
-----------------------
```bash
# Clone Git
git clone --recursive https://github.com/DO1JLR/ansible_thinkpad_setup.git ansible_thinkpad_setup

# go into the folder
cd ansible_thinkpad_setup

# Download needed submodules
git submodule update --init --recursive
```

 Which playbook?
---------------
L3D use different playbook for different workstations.<br/>
Maybe he change this in the future... But now this is the current state.

To use this by yourself copy or change a existing playbook and modify the variables.

Or create a new git repo and be inspired by the roles L3D uses.


 Feedback
------------
If you find this usefull please take a few secounds and say thankyou to L3D.

He is at the most [chaos ecents](https://events.ccc.de), simple give him a Tschunk or Club Mate there!
