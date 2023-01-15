# General post install

### TO-DO

- Enable `paccache.timer` to clear the package cache weekly. [More details](../user-story/commands.md)

- If using an SSD, enable `fstrim.timer` to discard unused blocks periodically.

- Setup a firewall such as `ufw` or `firewalld`.

- Install and configure `reflector` to frequently update the mirrorlist automatically.
 
- Enable Parallel Downloads in ` /etc/pacman.conf`.
 
- Install `intel-ucode` or `amd-ucode ` microcode depending on your CPU.
 
- For laptops, setup CPU frequency scaling and optimise battery life with `tlp`, `autocpu-freq`, `powertop` or `power-profiles-daemon` etc...
 
- Install a backup kernel like LTS or Zen kernel.
 
- For NVIDIA users, create a `pacman hook` to ensure initramfs gets updated on every nvidia or kernel upgrade.
 
- Install `noto-fonts` for basic font coverage.
 
- Optionally, replace `PulseAudio` with `PipeWire`.