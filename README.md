# home-assistant-tuya-custom

[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

A Home Assistant integration for adding custom Tuya categories without waiting for Core to update.
This code Home Assistanmt Core pull request and to allow quick additon of more devices.


This was originally a fork of jsmeyers/home-assistant-tuya-custom (https://github.com/jsmeyers/home-assistant-tuya-custom) but since 06/May/2023 I started it from scratch using the original TUYA folder from HomeAssistant/Core

This adds 2 different water irrigation valves named ‘GGQ’ (Diivoo dual zone irrigation kit) and ‘SFKZQ’ (Johgee single valve)


To add this repo as a custom component in home assistant:

Go to HACS
Integrations
3 Dots on top right corner
Custom repositories
repository: https://github.com/lasry1/home-assistant-tuya-custom/
Category: Integration


Then you'll need to install it and reboot home assistant

Hope that helps somebody as I struggled for years adding my irrigation natively to home asssitant.

