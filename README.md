# Advanced-Machine-learning

imagenet_dgl.py
To run end to end code:
python imagenet.py IMAGENET_DIR --arch resnet152 --half --dynamic-loss-scale -j THREADS

cifar_buffer.py
It contains the evaluation of asynchronous version of Decoupled greedy algorithm.
An example using M=30 slowing down layer 3(of 6 layers) by a factor of 1.1
python cifar_buffer.py --buffer 30 --noise 0.1 --layer_noise 3 --seed 0
