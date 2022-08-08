## conda 环境管理常用命令

### 1.创建环境：
	conda create -n env_name python=3.7

### 2.查看所有环境：
	conda info --envs
### 3.删除一个环境：
	conda remove -n env_name --all
### 4.激活 superset 环境
	 conda activate superset
### 5.退出当前环境
	 conda deactivate
### 5.重命名虚拟环境
	conda create -n [newenv] --clone [oldenv]
	conda remove -n [oldenv] --all