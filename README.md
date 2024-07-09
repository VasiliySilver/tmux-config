# tmux-config

### Step 1: Install Tmux

Open a terminal and run the following command:

```bash
sudo apt install tmux
```
This will install tmux on your system.

### Step 2: Clone TPM Repository

Run the following command to clone the TPM repository:

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
This will clone the TPM repository to the ~/.tmux/plugins/tpm directory.

### Step 3: Download Your Custom ~/.tmux.conf File

Run the following command to download your custom ~/.tmux.conf file from your repository:

```bash
curl -o ~/.tmux.conf https://raw.githubusercontent.com/VasiliySilver/tmux-config/main/.tmux.conf
```

This will download your custom ~/.tmux.conf file from your repository.

### Step 4: Initialize TPM

Run the following command to initialize TPM:

```bash
tmux source ~/.tmux.conf
```
This will reload your tmux configuration and initialize TPM.

That's it! You should now have tmux and TPM installed with your custom configuration. 

**You can press C-Space I to install plugins using TPM.**
