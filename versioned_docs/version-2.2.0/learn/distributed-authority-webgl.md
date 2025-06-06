---
id: distributed-authority-webgl
title: Distributed authority and WebGL quickstart
---

Use this guide to learn how to create your first [distributed authority](../terms-concepts/distributed-authority.md) Netcode for GameObjects WebGL project.

This guide is intended as an addition to the [distributed authority general quickstart](distributed-authority-quick-start.md) page, which provides more details about setting up Netcode for GameObjects to use distributed authority.

:::note Pricing
The distributed authority service provided by the [Multiplayer Services package](https://docs.unity.com/ugs/en-us/manual/mps-sdk/manual) offers a free tier for bandwidth and connectivity hours, allowing you to develop and test without immediate cost. Refer to the [Unity Gaming Services pricing page](https://unity.com/products/gaming-services/pricing) for complete details.
:::

## Prerequisites

Before you begin, you need the following general requirements to use the distributed authority network topology:

- An active Unity account with a valid license.
- The [Unity Hub](https://unity.com/download).
- A supported version of the Unity 6 Editor. Refer to the [Netcode for GameObjects requirements](https://docs-multiplayer.unity3d.com/netcode/current/installation).
    - When installing the Editor, make sure to include the __WebGL Build Support_ module.

You also need the following packages and minimum versions for a WebGL distributed authority session:

- Netcode for GameObjects version 2.1.1+
- Unity Transport version 2.3.0+
    - Note that you don't need to create a self-signed certificate to connect to a distributed authority session.
- Multiplayer Services version 1.0.2+

## Create and set up your project

Follow the instructions on the [distributed authority general quickstart](distributed-authority-quick-start.md) page.

## Build and run with WebGL

1. Navigate to __File__ > __Build Profiles__ to open the __Build Profiles__ window. Select WebGL as your target platform.
1. From the __Build Profiles__ window, click __Build and Run__.
    - Unity launches a small web hosting app to provide the HTTP services required to launch the WebGL application in your browser.
1. Once you have one instance of your WebGL project running, you can copy the URI from your browser and paste it into another window or tab, which creates and connects another player to the same session.
