# face-obfuscation
This is a toy example of [A Study of Face Obfuscation in ImageNet](https://arxiv.org/abs/2103.06191).  

[Kaiyu Yang](https://www.cs.princeton.edu/~kaiyuy/), [Jacqueline Yau](https://www.linkedin.com/in/jacqueline-yau-836b0a132/), [Li Fei-Fei](https://profiles.stanford.edu/fei-fei-li), [Jia Deng](https://www.cs.princeton.edu/~jiadeng/), and [Olga Russakovsky](https://www.cs.princeton.edu/~olgarus/) 
```
@article{yang2021imagenetfaces,
 title={A Study of Face Obfuscation in ImageNet},
 author={Yang, Kaiyu and Yau, Jacqueline and Fei-Fei, Li and Deng, Jia and Russakovsky, Olga},
 journal={arXiv preprint arXiv:2103.06191},
 year={2021}
}
```


I used **MTCNN** model from [facenet_pytorch](https://github.com/timesler/facenet-pytorch) to detect a face and original **blur code** from [imagenet-face-obfuscation](https://github.com/princetonvisualai/imagenet-face-obfuscation).  


[Note] Please visit each github to check the license.


## Requirements
- python 3.6 and upper.
- torch == 1.8.1 (for MTCNN)
- torchvision == 0.9.1 (for MTCNN)
- facenet-pytorch == 2.5.2
- matplotlib == 3.3.4
- numpy == 1.19.5

Specified in requirements.txt
```
pip install -r requirements.txt
```

## Result
![result](https://user-images.githubusercontent.com/21357649/119225536-4b901680-bb3f-11eb-8686-088993ccfedb.png)

