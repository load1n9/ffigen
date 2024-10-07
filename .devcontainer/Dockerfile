# Use the latest Arch Linux base image
FROM archlinux:latest

# Update system and install base-devel group
RUN pacman -Syu --noconfirm base-devel

# Install other necessary packages
RUN pacman -S --noconfirm git vim python

# Any other setup steps
RUN pacman -Sy deno mingw-w64-x86_64-clang mingw-w64-x86_64-clang-tools-extra gcc cmake ninja
