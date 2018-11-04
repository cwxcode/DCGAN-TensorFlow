# DCGAN-TensorFlow
功能：实现验证码生成
====================================================
./data  文件夹下放训练图片数据
./samples  文件夹下保存生成的图片
main.py  训练文件
model.py  模型文件
====================================================
注意：
输入图片的尺寸要全部相同

训练命令
python main.py --dataset yzm --input_height=48 --input_width=120 --output_height=48 --output_width=120 --input_fname_pattern *.png --learning_rate 0.000001 --train

测试命令
python main.py --dataset yzm --input_height=48 --input_width=120 --output_height=48 --output_width=120 --input_fname_pattern *.png

p.s. 如需数据集可联系作者本人
