# 3d_printer_light_controller

For controlling LED strip on 3D printer. Runs on a Raspberry Pi 4 with octoprint. Alexa skill interface for remotely turning light on and off. Also has a shutter mode useful for turning the lights on only when a snapshot is taken for the timelapse. Responds to SIGUSR1 and SIGUSR2 signals to handle start and stop of shutter. 
