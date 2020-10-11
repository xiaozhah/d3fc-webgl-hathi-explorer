
# UniNet: A Sequence-to-Sequence Model for Concatenative Speech Synthesis

## Speech demos
https://xiaozhah.github.io/UniNet_speech_demos

## t-SNE visualization of the phone-dependent distributions of the unit embeddings
![image](vis_unit_vectors.jpg)

### online interactive demos
* [UniNet encoder](https://xiaozhah.github.io/Visualization-of-Unit-Embeddings/UniNet%20encoder)
* [UniNet decoder](https://xiaozhah.github.io/Visualization-of-Unit-Embeddings/UniNet%20decoder)
* [Tacotron2 encoder](https://xiaozhah.github.io/Visualization-of-Unit-Embeddings/Tacotron2%20encoder)

### demos with audio on YouTube
* [UniNet encoder](https://youtu.be/Jne83LuJ28o)
* [UniNet decoder](https://youtu.be/xUDTWeyf9Ps)
* [Tacotron2 encoder](https://youtu.be/0Yrf6dRKhd4)

### offline interactive demos
```
git clone https://github.com/xiaozhah/Visualization-of-Unit-Embeddings.git
cd Visualization-of-Unit-Embeddings
# python3 -m http.server 
# python2
python -m SimpleHTTPServer
# then open http://localhost:8000 in Chrome
```
