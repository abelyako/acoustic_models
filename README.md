# Acoustic models
This repository contains pre-trained acoustic models for Russian language based on Voxforge ru and Kaldi

### Models

Since git doesn't allow store more than 1Gb, you can find pre-trained models here

[![N|Solid](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsX9SxCdcU0ITwfPlDdyrAwGc4jpwtEBnRvTcIEjlRyJUoQrWhgQ)](https://drive.google.com/open?id=0B3WyramYdFDnbHpsOHlUWFZzRXc)

This command line demonstrates how to run acoustic model tri2a 
>  online-wav-gmm-decode-faster —verbose=1 —rt-min=0.8 —rt-max=0.85 —max-active=4000 —beam=12.0 —acoustic-scale=0.0769 scp:input.scp ../final.mdl ./HCLG.fst ./words.txt 1:2:3:4:5 ark,t:./trans.txt ark,t:./ali.txt

### Links

Links to open source code for this projects could be found below

| Framework | Link |
| ------ | ------ |
| Kaldi | https://github.com/kaldi-asr/kaldi |
| Voxforge ru | https://github.com/freerussianasr/recipes/tree/master/voxforge_ru |
