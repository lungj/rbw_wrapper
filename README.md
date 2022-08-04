# rbw_wrapper
Wrapper for rbw to map a few commands to the official Bitwarden CLI form.

Speeds up use of Ansible
 - `community.general.bitwarden`,
 - `community.general.bitwarden_info`
 - bitwarden lookup module in community.general.

Requires
  - `rbw` (`cargo install rbw`);
  - `jq`;
  - Official bitwarden client named `bw_official`; and
  - Both `rbw` and `bw_official` must be unlocked.
