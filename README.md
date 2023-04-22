# NixOS Scripts

The NixOS config file provides a quick and easy way to deploy my current NixOS configuration, along with all programs that I use frequently.

**Please note that I am not responsible for any damage to your system. Please use my config at your own risk!**

This Nix Config provides the following programs:
<li>vim</li>
<li>wget</li>
<li>git</li>
<li>vscode</li>
<li>Google Chrome Dev</li>
<li>flatpak</li>
<li>tailscale</li>
<br>

To switch to the new config, simply run: **sudo nixos-rebuild switch**.

To perform updates, simply run **sudo nixos-rebuild boot — upgrade**.

To clean up old configurations, run **sudo nix-collect-garbage — delete-older-than 30d**.

