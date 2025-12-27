environment.yml文件包含创建可运行我们代码的虚拟环境的信息，可以作为参考，也可以根据下面步骤配置和我们一样的环境  
创建环境：conda env create -f environment.yml  
激活环境：conda activate rechorus  
针对 Mac 用户：如果安装失败，请删除 .yml 中的 pytorch 相关行，并参考 PyTorch 官网安装适配 Mac 的版本。  
请确保你的项目文件夹路径里没有中文。  
下面是可供测试的测试运行代码：  
python main.py --model_name FuXiAlpha --dataset MovieLens _1M --epoch 5 --batch_size 1024 --emb_size 32 --lr 0.001 --num_layers 1 --num_heads 2 --gpu 0
