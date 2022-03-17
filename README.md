# MIMO DFRC
## STAGE 1: RADAR TARGET SEARCH AND COMMUNICATION CHANNEL ESTIMATION
### A. Pilot Signal Generation Using Hybrid Structure

导频信号满足空间正交性

${{\mathbf{R}}_{s}}=\frac{1}{T}{{\mathbf{S}}_{DP}}\mathbf{S}_{DP}^{H}=\frac{P}{{{N}_{t}}}{{\mathbf{I}}_{{{N}_{t}}}}$

空间波形

${d\left( \theta  \right)={{\mathbf{a}}^{T}}\left( \theta  \right){{\mathbf{R}}_{s}}{{\mathbf{a}}^{*}}\left( \theta  \right)=P,\text{ }\forall \theta }$

将信号矩阵分解为基带信号（baseband）和模拟预编码矩阵

${{\mathbf{S}}_{DP}}={{\mathbf{F}}_{RF}}{{\mathbf{S}}_{BB}}$

定义初始时刻的基带信号矩阵和模拟预编码矩阵

${\mathbf{F}_{RF}^{1}={{\mathbf{1}}_{{{N}_{t}}}}\mathbf{1}_{{{N}_{RF}}}^{T} }$

${{\mathbf{S}}_{BB}}\left( :,1 \right)=\sqrt{\frac{P}{N_{RF}^{2}{{N}_{t}}}}{{\mathbf{1}}_{{{N}_{RF}}}}$

t+1时刻迭代

$\mathbf{F}_{RF}^{t+1}=\operatorname{diag}\left( \mathbf{u} \right)\mathbf{F}_{RF}^{t}$

${{\mathbf{S}}_{BB}}\left( :,t+1 \right)={{\mathbf{S}}_{BB}}\left( :,t \right){{v}_{t}}$

$\mathbf{u}={{\left[ {{u}_{1}},{{u}_{2}},\cdots ,{{u}_{{{N}_{t}}}} \right]}^{T}}$

${{u}_{n}}=\exp \left( \frac{j2\pi n}{T} \right),\text{ }{{v}_{t}}=\exp \left( \frac{j\pi \left( 2t-1 \right)}{T} \right)$

**仿真实验**

[![qC1X6g.gif](https://s1.ax1x.com/2022/03/17/qC1X6g.gif)](https://imgtu.com/i/qC1X6g)

### B. Parameter Estimation After
### C. Identifying Communication Channel Paths from Targets


