# GFPGAN-Video-SuperResolution

This Colab notebook demonstrates how to perform Video Super-Resolution (SR) using GFPGAN. The process involves extracting frames from videos, applying super-resolution to the frames, and then reassembling the enhanced frames into high-quality videos.

## Requirements:
- BasicSR (installed via GitHub)
- GFPGAN
- Facexlib
- RealESRGAN
- FFmpeg (for video format conversion)

## Usage:
1. **Clone this repository** and open the `GFPGAN_Video_SR.ipynb` in Google Colab.
2. **Upload videos** to the `videos` folder.
3. **Run the notebook** to process the video (restores faces and upscales background).
4. Results will be available in the `results_mp4_videos` folder for download.

## Steps:
1. **Install dependencies**: BasicSR, GFPGAN, Facexlib, and RealESRGAN.
2. **Prepare directories** for input and output (videos, results).
3. **Run inference** to apply super-resolution to each frame.
4. **Reassemble frames** into an enhanced video.
5. Convert the output to MP4 format for easy sharing.

## How to Run:
1. Upload a video to the `videos` folder.
2. Execute the notebook cell to process and enhance the video.
3. Download the output from the `results_mp4_videos` folder.

## License:
This project is licensed under the MIT License.

