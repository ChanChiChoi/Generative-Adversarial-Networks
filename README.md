# Generative-Adversarial-Networks

after read the GAN papers, I find the excellent code in github, then decouple them and extract the kernel part（or write by myself） into ipython notebook for easy understanding。   

The below ipynbs use mnist for training and inferencing     
vanllia_GAN:   
<div align=center><img src="result/vanilla_gan_5700.jpg"  align=center /></div>
<div align=center>setp=5700</div>
conditional_GAN:    
<div align=center><img src="result/cgan_24900.jpg"  align=center /></div>
<div align=center>setp=24900</div>
DCGAN:
<div align=center><img src="result/DCGAN_5700.jpg"  align=center /></div>
<div align=center>setp=5700</div>
EBGAN:
<div align=center><img src="result/ebGAN_5700.jpg"  align=center /></div>
<div align=center>setp=5700</div>
LSGAN:
<div align=center><img src="result/LSGAN_oneclass_5700.jpg"  align=center /> <img src="result/multi_5700.jpg"  align=center /></div>
<div align=center>setp=5700.left:without conditional ; right:with conditional</div>  
AAE Label information incorporating:   
<div align=center><img src="result/AAE_LabelInfo_5700.gif "  align=center /> <img src="result/ AAE_LabelInfo_scatter_5700.gif"  align=center /></div>
<div align=center>setp=5700.left:Learned MNIST manifold ; right:Distribution of labeled data</div>  
