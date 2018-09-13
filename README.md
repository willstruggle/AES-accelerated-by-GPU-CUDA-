# AES-accelerated-by-GPU-CUDA-
AES accelerated by GPU(CUDA)
The project is mainly concentrate on the accelerating implements of crypto alogoritm AES in GPU.The program code is writen by CUDA.By optimism the threads and memry ,we finally approach to 110Gbps throughts of AES and which make a big progress.

#Experience Platform:
 ubuntu 16.04
 Nvidia Titan XP GPU

(but you can still run the code on your own device, the only requirements is you have a Nvidia GPU.)

#Compile and implementation example :
  nvcc -o AES AES.cu
  ./AES plain.txt key.txt encryption.txt
