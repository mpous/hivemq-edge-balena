# HiveMQ Edge running on balena

This is an industrial edge reference architecture running HiveMQ Edge with an embedded MQTT broker and an Edge UI to connect the edge device with PLCs and others. This IIoT edge gateway is running on a balena.

You can read more information on the [HiveMQ Edge repository](https://github.com/hivemq/hivemq-edge).


## Deploy the code

Running this project is as simple as deploying it to a balenaCloud application. You can do it in just one click by using the button below:

[![](https://www.balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/mpous/hivemq-edge-balena)

Follow instructions, click Add a Device and flash an SD card with that OS image dowloaded from balenaCloud. Enjoy the magic 🌟Over-The-Air🌟!

## Log in

The HiveMQ Edge service is exposed on the 8080 port. You can access to the UI using the local IP address or the Public Device URL (without https) with the port 8080.

|Service|Port|Username|Password|
|:--|---|---|---|
|HiveMQ|8080 (http)|admin|hivemq|


## Attribution

- This is in part working thanks of the work of [Kudzai Manditereza](https://github.com/kmanditereza) from HiveMQ and Marc Pous from balena.io.


## Troubleshooting

If you detect any issue using this block, feel free to contact us at the [forums.balena.io](https://forums.balena.io).

