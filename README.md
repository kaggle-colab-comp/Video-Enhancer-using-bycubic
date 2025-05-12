# Video-Enhancer-using-bycubic
The motivation of the project is that i downloaded 500 episodes of Naruto shipuuden worth of 135gb but the video quality is not up to my standards so i am genrating a code that would upscale the anime

this code uses bycubic facotor to upscale the results 
the results are not that satisfactory i am working on realESRGAN to upscale the videos.
before running the requiremnts.txt check below things
i am using Ubuntu 22.04.5 as operating system all the work done is in the virtual envirnment
to run the envirnment run the bellow cammands in the terminal
the jupyter notebook is also running in the virtual envirnment so activate the envirment for both the jupyter notebook and to run the installation files
the commands are

python3 -m venv venv
 source venv/bin/activate


incase you run jupyter lab
if you gets some error run following commands in the terminal then restart the jupyter notebook


jupyter nbextension enable --py widgetsnbextension
jupyter nbextension install --py widgetsnbextension
jupyter labextension install @jupyter-widgets/jupyterlab-manager


in the terminal instal the ffmpeg

sudo apt update
sudo apt install ffmpeg
