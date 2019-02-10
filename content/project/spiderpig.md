+++
title = "Spider Pig"
sub_title = "Autonomous Hexapod Robot."

date="2016-06-01" # (only used for the projects to be listed in the correct order)

start_date = "Jan 2016"
end_date = "Jun 2016"

project_type = "Bachelor thesis project, Linköping University"

software = "C"

# Image thumbnail:
image_preview = "spiderpig.png"

# Links:
url_preprint = ""
url_code = "https://github.com/Skipsterino/Kandidatprojekt"
url_dataset = ""
url_project = ""
url_video = "https://youtu.be/N5_tMeEpJaA"
url_slides = "https://drive.google.com/file/d/0B-n8kwzkfV_fZzFONTlqa3hockU/view?usp=sharing"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Report", url = "https://drive.google.com/file/d/0B-n8kwzkfV_fM1hqVU1uZkxTYlU/view?usp=sharing"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image="thesis_color.png" # (full-width header image)
#small_image = "thesis_color.png" # (header image the same size as the article)
video="https://www.youtube.com/embed/N5_tMeEpJaA?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++

<p>
    <b>Main hardware:</b><br>
        - 1x PhantomX AX Metal Hexapod Mark II Kit (including 18x Dynamixel AX-12 servos, excluding the ArbotiX Robocontroller).<br>
        - 3x ATmega1284p microcontrollers.<br>
        - 7x IR distance sensors.<br>
        - 1x ultrasonic distance sensor.<br>
        - 1x MPU-6050 IMU.<br>
        - 1x LCD display.<br>
        - 1x FireFly Bluetooth modem.<br>
        - 1x Raspberry Pi 3 Model B.<br>
        - 1x Raspberry Pi Camera Board 5 MP.<br>
    <br>

    <b>Functionality:</b><br>
    - The robot can navigate a simple maze (containing both low and high obstacles) autonomously and be controlled manually with an Xbox controller connected to a PC. It communicates with the PC over Bluetooth.<br>
    - The system is divided into three subsystems (control, sensors and communication), with one microcontroller each. The subsystems communicate via an SPI bus.<br>
    - The Raspberry Pi is configured as a WiFi hotspot and streams video to a Linux computer.<br>
    - The walking algorithm is based on inverse kinematics. A PD controller is used to keep it centered in corridors.
</p>

By Fredrik K. Gustafsson, Joakim Bertils, Jonas Ehn, Kevin Kjellén, Erik Ljungzell, Christoffer Malmgren and Jens Månsson.

My main responsibilities: Sensors and autonomy.
