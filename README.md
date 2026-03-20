<h1 align="center">soulfetch</h1>
<p align="center">"fetches thy soul"</p>

[soulfetch](https://github.com/user-attachments/assets/3af64391-1300-4d75-8429-d417419e97d4)

Installation:
```bash
# clone the repo
git clone https://github.com/that-ponderer/soulfetch.git --depth 1
# copy the executable, make sure you have "$HOME/.local/bin" in your $PATH
cp soulfetch/soulfetch "$HOME/.local/bin"                         
```
Intel gpus:
> [!IMPORTANT]
> ```bash
> # the intel_gpu_top util needs the cap_perfmon capability to function
> sudo setcap "CAP_PERFMON=+ep" $(which intel_gpu_top)
> ```
Dependencies:
```bash
# Note: only 
# External Utils
```
