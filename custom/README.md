# Usage note

## 1. init. dataset 

```bash
# classids.json
wget https://raw.githubusercontent.com/facebookresearch/video-nonlocal-net/main/process_data/kinetics/classids.json
```

```bash
# gen_py_list.py
wget https://raw.githubusercontent.com/facebookresearch/video-nonlocal-net/main/process_data/kinetics/gen_py_list.py
```

after then, run the code like below to generate ```trainlist.txt``` . 

```bash 
python gen_py_list.py
```

```bash
# to rescale the videos to height=256 pixels
wget https://raw.githubusercontent.com/facebookresearch/video-nonlocal-net/main/process_data/kinetics/downscale_video_joblib.py
```


## 2. ```DATA.PATH_TO_DATA_DIR``` path_to_your_dataset
* refer to [issue #458](https://github.com/facebookresearch/SlowFast/issues/458)




## 3. For VScode debugging 
* refer to this [link](https://jeremybytes.blogspot.com/2020/02/set-working-directory-in-visual-studio.html)
* [VScode Debug 시작 경로 변경](https://blog.naver.com/PostView.nhn?blogId=sjy263942&logNo=222326679448)



