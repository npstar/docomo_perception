docomo_perception
- - -

*NOTE: now deb version of `sound_play` has no support action server. So you should `git clone https://github.com/ros-drivers/audio_common` in your catkin work space and `catkin_make`.*

1. register app and get api key from docomo developer support.

https://dev.smt.docomo.ne.jp/?p=index

*NOTE: you have to enable function which you'd like to use, when register app.*

2. put api key into `cfg/docomo-<service>-settings.yaml`, and copy yaml files to `settings_path`

3. enjoy!
