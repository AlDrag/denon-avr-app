# Denon AVR Remote

Cross Platform Ionic app that controls your Denon AVR with a more intuitive interface compared to the official Denon Remote app.

## How does it interface with your AVR?

It makes use of the `POST /goform/AppCommand.xml` API on the Denon AVR device. Details about the payloads available using this interface is already documented here: https://github.com/ol-iver/denonavr/blob/main/doc/XML_data_dump.txt, thank you to them.