+++
title = "Rasperino"
sub_title = "Autonomous/Web Controlled Raspberry Pi & Arduino Robot."

date="2016-07-01" # (only used for the projects to be listed in the correct order)

start_date = "Jun 2016"
end_date = "Aug 2016"

project_type = "Personal project"

software = "Python, C, HTML, JavaScript"

# Image thumbnail:
image_preview = "rasperino.png"

# Links:
url_preprint = ""
url_code = "https://github.com/fregu856/Sommarprojekt16"
url_dataset = ""
url_project = ""
url_video = "https://youtu.be/povGte7K8o4"
url_slides = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Images", url = "https://goo.gl/photos/z78dbTpEZ5kwjqneA"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image="thesis_color.png" # (full-width header image)
#small_image = "thesis_color.png" # (header image the same size as the article)
video="https://www.youtube.com/embed/povGte7K8o4?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++

<p>
    <b>Main hardware:</b><br>
        - 1x Arduino Uno.<br>
        - 1x Raspberry Pi 3 Model B.<br>
        - 1x Raspberry Pi Camera Module v2.<br>
        - 1x DFRobot 4WD Arduino Mobile Platform.<br>
        - 2x L298 Dual H-Bridge DC Motor Controller.<br>
        - 5x Sharp GP2Y0A21YK0F IR Range Sensor - 10 cm to 80 cm.<br>
        - 1x Power bank.<br>
    <br>

    <b>Features:</b><br>
        - Autonomous navigation of simple mazes.<br>
        - Basic computer vision for detection of "color signs".<br>
        - Video streaming.<br>
        - Web interface for manual control and monitoring (desktop & mobile).<br>
        - PD controller.<br>
    <br>

    <b>Functionality:</b><br>
        - The Arduino reads and filters the IR sensors, implements the PD controller, controls the motor controllers via PVM and runs a state mahcine for autonomous navigation.<br>
        - The Raspberry Pi acts as a webserver, streams live video and runs a basic computer vision algorithm.<br>
        - The Arduino sends sensor and status data to the Raspberry Pi over serial (USB cable), which in turn sends this (and video streaming data) to the web page over WiFi.<br>
        - User input is sent from the web page to the Raspberry Pi over WiFi, which in turn sends this to the Arduino over serial.
</p>
