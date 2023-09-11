# Open-Source AI Video Dubber

### *Automatically dub any video into English while keeping the original voice styles*

### Setup:
1. Clone the repo: *git clone https://github.com/EliasLindbergs/ai-video-dubber.git*
2. Download the following pre-trained models and place them in the corresponding folders:
- epoch_2nd_00050.pth (download link: https://drive.google.com/file/d/1nm0yB6Y5QWF3FYGfJCwQ6zYNlOAYVSet/view) in Models/LibriTTS
- g_00935000 (download link: https://drive.google.com/file/d/1RDxYknrzncGzusYeVeDo38ErNdczzbik/view) in Vocoder/LibriTTS
3. In the inference notebook, replace API_KEY with your OpenAI API key (https://platform.openai.com/account/api-keys) and AUTH_TOKEN with your pyannote access token (visit hf.co/pyannote/embedding and accept user conditions, then visit hf.co/settings/tokens to create an access token)

### Run:
1. Re-name your video to “video.mp4” (or whatever extension it has) and place it in a Media folder
2. Run the inference notebook and collect the generated dubbed video "final_video_output.mp4" in the Media folder

### References:
- https://github.com/tsurumeso/vocal-remover
- https://github.com/facebookresearch/denoiser/tree/main
- https://github.com/openai/whisper
- https://github.com/pyannote/pyannote-audio
- https://platform.openai.com/docs/api-reference/chat
- https://github.com/yl4579/StyleTTS

### *Your contributions are more than welcome!*
