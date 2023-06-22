# Key-Frames-Extraction-and-Object-Detection

## In order to extract key frames from a video, an awesome Python library ***KATNA*** helps out in better video processing like extracting key frames, compressing videos and etc... 

Here is the sample video:

https://github.com/HarisudhanVL/Key-Frames-Extraction-and-Object-Detection/assets/68286374/745d4505-c8d8-434b-97a7-d2538a82035c

Applying the below code to the above video, the keyframes are extracted: 

if __name__ == "__main__": \
    vd = Video() \
    no_of_frames_to_returned = 12 \
    diskwriter = KeyFrameDiskWriter(location=r"D:\Tann Mann Intership\Interview task\KeyFrames") ## Saving the frames locally. \
    video_file_path = os.path.join(".", "tests", "data", "D:\Tann Mann Intership\Interview task\\video.mp4") ## Input video. \
    print(f"Input video file path = {video_file_path}") \
    vd.extract_video_keyframes(no_of_frames=no_of_frames_to_returned, file_path=video_file_path, writer=diskwriter) ## Extracting Keyframes.'''

