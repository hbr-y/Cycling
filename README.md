# Cycling

orgフォルダの中のzipは解答してorg直下においてから使ってください。

25MB以上のファイルがおけなかったので。

|パターン|validation|本番|データセット|
|---|---|---|---|
|チュートリアル|2.1174103783112748|4.1862687||
|改善1 RF|2.383682306027287||station_id,bikes_available_at0,hour_1～24,week1～7,city_1～5,events|
|改善1 GBR|2.3796365185729873|4.0403259|同上|
|出入の平均追加 RF|2.297460091241068|4.1873841|station_id,bikes_available_at0,start_num_ave,end_num_ave,hour_1～24,week1～7,city_1～5,events|
|出入の平均追加 GBR|2.3133075752031567|4.0820157|station_id,bikes_available_at0,start_num_ave,end_num_ave,hour_1～24,week1～7,city_1～5,events|
|at0無 GBR|3.0168495435201974|3.6336039|station_id,hour,week1～7,city_1～5,events|
|at0無 1-6,7-23 GBR||3.9308063|station_id,hour,week1～7,city_1～5,events|
|at0無 city2,other GBR||3.7927864|station_id,hour,week1～7,city_1～5,events|
|at0無 出入り平均 GBR||3.6582320|station_id,start_num_ave,end_num_ave,hour,week1～7,city_1～5,events|

