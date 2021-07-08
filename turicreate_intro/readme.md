# Turicreate

Turi Create simplifies the development of custom machine learning models. You don't have to be a machine learning expert to add recommendations, object detection, image classification, image similarity or activity classification to your app.

- Easy-to-use: Focus on tasks instead of algorithms
- Visual: Built-in, streaming visualizations to explore your data
- Flexible: Supports text, images, audio, video and sensor data
- Fast and Scalable: Work with large datasets on a single machine
- Ready To Deploy: Export models to Core ML for use in iOS, macOS, watchOS, and tvOS apps

Turicreate, can be used in Google Colab or localy, 

### Installing in Collab

``` Python
pip install turicreate
import turicreate as tc
````
### Installing on windows10  subsytem

1. enable 'windows subsytem' as open Powershell as administrator, and use the following command.
  `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux` \
  
  **This will require a restart.**

2. Launch MS store, search of Linux \ 
  Select the Linux distrubtion of your choice, for example *Ubuntu 18.04 LTS distro* \
  Select get and install
  
3. Launch distro Ubunto, next will be some prompts to setup a new linux account \
  create username and password
 
4. Update and upgrade packages \
  `sudo apt update && sudo apt upgrade`
5. Install dependencies \
  `sudo apt-get install -y libstdc++6 python-setuptools` \
  `sudo apt-get install python3-pip`
6. Install your virtual environment with PIP3 \
  `sudo pip3 install virtualenve`
7. Create envirnment \
  `virtualenv venv`
8. Activate your new environment
  `source venv/bin/activate`
9. Install Jupyter Noteboos \
  `pip3 install jupyter`
9 Install Turicreate
  `pip 3 install jupyter`
10. Run notebooks \
  `jupyter notebook`
11. You will need to coppy paste the server link into your browser. there will be two links either is fine.
  copy and paste one of these URLs:
  `http://localhost:8888/?token=ce9dcc66cb9b6cae0054052e0a22f4b9fffc5ddaf1f` \
  `http://127.0.0.1:8888/?token=ce9dcc66cb9b6cae0054052e0a22f4b9fffc5ddaf1f`

### Visual Studio Code
you can use the sub system in VSCode
1. `View` -> `Command Pallet` or use Ctrl+Ahift+P
2. search for `remote-wsl` and select this will open up a new window, and will be in the subsytem


  



