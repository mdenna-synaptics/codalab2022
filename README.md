# Codalab 2022 Timings

The report.json file contains inference times for all submissions which have been
successfully evaluated.

For each submission ID the file contains:
- author, filename and date of the submission
- total inference time (in us) of the quantized model on the Synaptics VS680 EVK board
- inference time by layer in us
- any error while compiling or running the model (“error” field)
- additional notes if any (“notes” field)


Top Inference Times NHWC
-------------------------------
ID      |  Inference   Author
------  |  ---------   --------
156713  |   11000 us   jetbrian 
156696  |   11140 us   ygcheng  
159940  |   11770 us   ykh1123  
159945  |   11830 us   ykh1123  
157995  |   12290 us   kkk      
156663  |   12660 us   ygcheng
157997  |   12760 us   kkk
158215  |   13210 us   ygcheng  
159731  |   13590 us   xiaokaoji
159717  |   13660 us   xiaokaoji


Top Inference Times NCHW
-------------------------------
ID      |  Inference   Author
------  |  ---------   --------
156713  |    4920 us   jetbrian
156696  |    5140 us   ygcheng
159940  |    5560 us   ykh1123
159945  |    5570 us   ykh1123
157995  |    6090 us   kkk
157997  |    6620 us   kkk
156663  |    6640 us   ygcheng
158215  |    7190 us   ygcheng
159731  |    7410 us   xiaokaoji
158601  |    7530 us   stevek
