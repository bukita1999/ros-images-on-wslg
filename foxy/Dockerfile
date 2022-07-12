FROM ros:foxy-ros-base-focal

# install ros2 packages
RUN apt-get update && apt-get install -y --no-install-recommends  \
    ros-foxy-desktop=0.9.2-1* \
    && rm -rf /var/lib/apt/lists/*

RUN apt-get update && apt-get install ros-foxy-gazebo-* vim

RUN add-apt-repository ppa:kisak/kisak-mesa  && apt-get update && apt -y dist-upgrade || apt --fix-broken install -y

