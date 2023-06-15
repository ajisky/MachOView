# MachOView 

该工程是建立在[轮子](https://github.com/gdbinit/MachOView)上的，感谢作者的贡献，经作者[fangshufeng](https://github.com/fangshufeng/MachOView.git)，维护下更新到v2.6.1, 最后一个版本更新已是4.5年前，后续版本由本人更新。

## v2.6.3 更新内容

修复eh_frame FDE中存在LSDA时, 解析gcc_except_tab结构出错导致crash问题


![](./mdimg/1686823009830.png)

## v2.6.2 更新内容

Load Command增加`Symbol LC_DYLD_CHAINED_FIXUPS `和`LC_DYLD_EXPORTS_TRIE`和`LC_BUILD_VERSION` 的识别，方便查找内容


![](./mdimg/1686629672946.png)

[2.6.3dmg](https://github.com/ajisky/MachOView/blob/Branch_support_new_loadcommand/releases/tag/2.6.3.dmg)

Engineering:  
	Peter Saghelyi  
	fG!  
	ArmVMP  
Other Product:  
	binaray vmp protect support arch :x86, x64, arm64, arm  
	support os platform: linux, windows, macos and ios  
	[ArmVMP](https://www.armvmp.com)  

如果帮到你就给个⭐️⭐️⭐️吧
