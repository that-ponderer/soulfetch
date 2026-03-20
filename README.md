<h1 align="center">soulfetch</h1>
<h3 align="center">"fetches thy soul"</h3>

[soulfetch](https://github.com/user-attachments/assets/3af64391-1300-4d75-8429-d417419e97d4)

Installation:
```bash
# clone the repo
git clone https://github.com/that-ponderer/soulfetch.git --depth 1
# copy the executable, make sure you have "$HOME/.local/bin" in your $PATH
cp soulfetch/soulfetch "$HOME/.local/bin"                         
```
Intel GPUs:
> [!IMPORTANT]
> ```bash
> # the intel_gpu_top util needs the cap_perfmon capability to function
> sudo setcap "CAP_PERFMON=+ep" $(which intel_gpu_top)
> ```

Dependencies:
```bash
# Note: only intel and nvidia gpu are supported.
# Core utils are required.
# External utils are optional, install the ones you need.
# 
# External Utils: 
nvidia-smi # from: nvidia-utils, for nvidia gpu support
intel_gpu_top # from: intel-gpu-tools, for intel gpu support
nerd-fonts (any variant) # glyphs used in animations

# Core utils (most likely already installed):

lspci
getcap 
tail 
df 
which 
mkdir 
sleep 
lsof 
fuser 
ps 
xprop 
uname 
whoami 
rm 
kill 
ip 
getopt 
stty 
```
