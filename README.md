# amr_description
Autonomous Mobile Robot

#### to download the amr:
go to catkin_ws/src
>git clone https://github.com/motomechatronics/amr_description.git
>
>git clone https://github.com/motomechatronics/aws_robomaker_small_warehouse_world.git

#### go to catkin_ws:

>catkin_make

#### to load the amr into the environment:

>roslaunch amr_description amr_warehouse.launch  

#### download teleop key:

>sudo apt-get install ros-melodic-teleop-twist-keyboard

#### open another shell:

>rosrun teleop_twist_keyboard teleop_twist_keyboard.py

<!-- GETTING STARTED -->
## amr_description

This is an example of an Autonomous Mobile Robot.

### Installation

Open a linux terminal and go to the _catlin_ws/src_ directory and type as follow:

  ```sh
  git clone https://github.com/motomechatronics/amr_description.git
  git clone https://github.com/motomechatronics/aws_robomaker_small_warehouse_world.git

  
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#top">back to top</a>)</p>
