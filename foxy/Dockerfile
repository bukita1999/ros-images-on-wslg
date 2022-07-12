FROM ros:foxy-ros-base-focal #from foxy ros-base

RUN apt update && apt-get install ros-foxy-desktop -y

RUN add-apt-repository ppa:kisak/kisak-mesa  && apt-get update && apt -y dist-upgrade || apt --fix-broken install -y

