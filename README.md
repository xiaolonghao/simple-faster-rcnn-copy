# simple-faster-rcnn-copy
整理simple-faster-rcnn的环境
cuda 9.0 pytorch 1.0.0 python 3.6.5 cupy 6.0.0 pillow 6.2.1等

1. pip install  cupy-cuda80 cupy-cuda90 cupy-cuda100 cupy-cuda101

2. cd model/utils/nms/
   python build.py build_ext --inplace
3. 修改voc_dataset.py 最后类别

4. python train.py
