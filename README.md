# Smart Life (Beta) Home Assistant Integration

[![GitHub license](https://img.shields.io/github/license/tuya/tuya-smart-life.svg)](https://github.com/tuya/tuya-smart-life/blob/main/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/tuya/tuya-smart-life.svg)](https://github.com/tuya/tuya-smart-life/graphs/contributors)
[![GitHub issues](https://img.shields.io/github/issues/tuya/tuya-smart-life.svg)](https://github.com/tuya/tuya-smart-life/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/tuya/tuya-smart-life.svg)](https://GitHub.com/tuya/tuya-smart-life/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/tuya/tuya-smart-life.svg?style=social&label=Watch)](https://GitHub.com/tuya/tuya-smart-life/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/tuya/tuya-smart-life.svg?style=social&label=Fork)](https://gitHub.com/tuya/tuya-smart-life/network/)
[![GitHub stars](https://img.shields.io/github/stars/tuya/tuya-smart-life.svg?style=social&label=Star)](https://GitHub.com/tuya/tuya-smart-life/stargazers/)

If you like Tuya Smart Life (Beta) Integration, please give it a star or fork it and contribute!

# Smart Life（Beta）Integration Documentation

<p align="center">
    <img src="https://images.tuyacn.com/app/hass/ha_tuya.png" width="70%">
</p>

The Smart Life（Beta）integration is developed for controlling **Powered by Tuya (PBT)** devices using the [tuya-device-sharing-sdk](https://github.com/tuya/tuya-device-sharing-sdk), and maintained by the official Tuya Developer Team. 

It is currently in **beta testing**, and there is still room for improvement in terms of functionality and stability. Feel free to install and try it out.

We really appreciate your contributions and awesome ideas to this project. We are happy to hear your voices at [GitHub Discussions](https://github.com/tuya/tuya-smart-life/discussions) to make our integration better. 

Please provide feedback to Tuya through [Github Issues](https://github.com/tuya/tuya-smart-life/issues/) to help us improve and optimize it.

## Important Note
### What's the difference between "Tuya" and "Smart Life" Integrations?

1. [Tuya Integration](https://www.home-assistant.io/integrations/tuya/) relies on [Tuya IoT Core Service subscription](https://iot.tuya.com/cloud/products/detail?abilityId=1442730014117204014), if the subscription has expired, the integration will stop working. Users are required to manually extend the trial subscription period, which can be inconvenient and frustrating.

2. Tuya Smart Life (Beta) integration has removed the Tuya cloud development workflow, allowing users to simply scan and log in using the [Smart Life app](https://developer.tuya.com/en/docs/iot/tuya-smart-app-smart-life-app-advantages?id=K989rqa49rluq), and then seamlessly sync their IoT devices directly to Home Assistant. It offers a simplified and efficient solution.

**Note:** If you are transitioning from the **Tuya Integration** to the **Smart Life (Beta) integration**, it may be necessary to set up all your devices again within your Smart Life app account. The migration process does not support directly transferring devices from one integration to the other.

## Installation Guide
[How to Install Smart Life Integration (Beta)](https://developer.tuya.com/en/docs/iot/Smart_Life_Integration?id=Kd0gk9baikbb7)

## Video Guide

[![Watch the video](./docs/video_image.png)](https://images.tuyaus.com/content-platform/hestia/16975151956db23d16f4d.mp4)

## Prerequisites

Your devices need to first be added in the [Smart Life app](https://developer.tuya.com/en/docs/iot/tuya-smart-app-smart-life-app-advantages?id=K989rqa49rluq).

## Supported Tuya Device Categories
Seven primary categories, 50 secondary categories are supported now!

:clap: [Supported Device Category](./docs/supported_devices.md)

## Follow Us

Follow us to get more information and leading technology on the Internet of Things, as well as updates and activities on the [Tuya IoT Developer Platform](https://developer.tuya.com/?_source=6d8d369b1b09336f622047669af507c4)

## Issue Feedback

You can give feedback on issues you encounter for the project via **GitHub Issue**.

## Related Projects

- [Tuya Device Sharing SDK](https://github.com/tuya/tuya-device-sharing-sdk)

## LICENSE

For more information, please refer to the [LICENSE](LICENSE) file.
