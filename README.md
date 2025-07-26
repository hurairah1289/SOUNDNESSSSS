# soundness

```bash
sudo apt update && sudo apt upgrade -y

curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash

source ~/.bashrc

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh

source $HOME/.cargo/env

soundnessup install

soundnessup update

# If you have old phrase then import your phrase and get back your old key:
soundness-cli import-key --name my-key --mnemonic "your 24 words phrase"

🆕 If you want to generate a new key then run this:
soundness-cli generate-key --name my-key
