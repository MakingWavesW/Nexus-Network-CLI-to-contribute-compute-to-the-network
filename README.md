# Nexus-Network-CLI-to-contribute-compute-to-the-network
The Nexus Network CLI is a command-line tool for contributing compute resources to the network.

 # 1. Instaling Linux
1.Open Windows Powershell<br>
2.Type Command"wsl -l -o" **(install the WSL-Windows Subsystem for Linux)** <br>
3.Than Type "wsl --install -d Ubuntu-24.04" **(This will install Ubuntu-24.04)**<br>
4.After installing **Ubuntu-24.04** Enter Username **(Example:- Nexus)** Add Password/Confirm it<br>

# 2. Install Script

## Manual Installation
1.Type "sudo -i" **Note:- type this after root@---Your Username---**<br>
2.Than paste it"sudo apt update && sudo apt upgrade"<br>
3.after that paste this  **(if asked for Y/N Type Y)**:-
"sudo apt install build-essential pkg-config libssl-dev git-all protobuf-compiler"
### Instal all the essential

## Start
1.After installing the Files Paste"curl https://cli.nexus.xyz/ | sh" **This will start the Nexus Web**<br>**(Make Sure to Restart or refresh your terminal (‘source ~/.bashrc, ‘source ~/.zshrc’, etc.). To start with an existing node ID, run:)**
3.Type "nexus-network start --node-id <your-node-id>"**(Like this nexus-network start --node-id 36920378)**<br>
4.Go to ""https://app.nexus.xyz/nodes"".In the Top right Corner Click **"ADD Cli Node"** Copy the node ID Add  it in the upper code **(Like this nexus-network start --node-id 36920378)**

# Congrats! you Node has been setup
