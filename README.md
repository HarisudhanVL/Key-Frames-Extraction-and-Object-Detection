# Key-Frames-Extraction-and-Object-Detection

## In order to extract key frames from a video, an awesome Python library ***KATNA*** helps out in better video processing like extracting key frames, compressing videos and etc... 

### Here is the sample video:

https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/745d4505-c8d8-434b-97a7-d2538a82035c

### Applying the below code to the above video, the keyframes are extracted: 


>if __name__ == "__main__": \
>&nbsp;&nbsp; vd = Video() \
 >   &nbsp;&nbsp; no_of_frames_to_returned = 12 \
 >   &nbsp;&nbsp; diskwriter = KeyFrameDiskWriter(location=r"D:\Tann Mann Intership\Interview task\KeyFrames") ## Saving the frames locally. \
 >   &nbsp;&nbsp; video_file_path = os.path.join(".", "tests", "data", "D:\Tann Mann Intership\Interview task\\video.mp4") ## Input video. \
 >   &nbsp;&nbsp; print(f"Input video file path = {video_file_path}") \
 >   &nbsp;&nbsp; vd.extract_video_keyframes(no_of_frames=no_of_frames_to_returned, file_path=video_file_path, writer=diskwriter)  Extracting Keyframes.

### And the Key Frames extracted are,
![video_0](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/de13781c-f790-4abf-9ef3-97dda02bf6f7)
![video_3](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/b37b13a4-f907-4bbc-b0d6-3c0cc18a20ea)
![video_2](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/0f70212f-935d-425c-b744-28fde9506114)
![video_1](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/b6e6266d-2242-4177-bd04-d38ec35adfd6)
![video_4](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/5dafd1b8-bf77-4daa-b21d-da3f0c1458ce)
![video_7](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/677b287c-c6f7-4541-856d-5a8bf2616e71)
![video_8](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/927803ed-e612-49b5-8e33-9731cb2871f4)
![video_10](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/722a80c4-a367-4045-96bd-1f722c12ce03)

### On performing object detection on these images using YOLOv3, the results are:

![Picture7](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/a284ebc2-d5b2-4e91-93a0-a48b85be62d0)
![Picture1](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/bb641656-cf77-4572-a76f-90aca4363dd4)
![Picture2](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/3e92fbad-9b08-407b-b97e-c4425dd3e333)
![Picture3](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/63ba02f1-69bc-44ec-842b-d0139ef0b26e)
![Picture4](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/369b84e8-8ab7-4b69-9771-25a300da7e15)
![Picture5](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/3f6823e4-20ee-4426-821e-48fbd32b2c97)
![Picture6](https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/812b5975-d16a-4880-a8b8-239bd9cde6d6)

The complete code is available at https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/blob/af9a8ae1e66fdda5132f6ce4079eeee1acd97b27/Key_Frames_and_YOLOv3_Model.ipynb



