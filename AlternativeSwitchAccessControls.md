# Alternative Switch Access Controls
Switch access is an assistive technology for computer use by people with severe
physical or cognitive impairment. Some people with those types of disability are
unable to type on a keyboard or click with a mouse, and unable to speak and use
speech recognition.

Current switch access products require dedicated control hardware. A switch
control could be a large button or a pair of large buttons, for example. The
control is connected to the computer or mobile device by a cable or by
Bluetooth.

It is proposed that general purpose hardware that is already present on typical
computers and mobile devices could be used instead of dedicated hardware. For
example:

-   Camera.
-   Fingerprint sensor.
-   Proximity sensor.
-   Microphone.
-   Accelerometer.

## Background
See the following for background.

-   Switch Access on Wikipedia:  
    [https://en.wikipedia.org/wiki/Switch_access](https://en.wikipedia.org/wiki/Switch_access)

-   Switch Access for Android:  
    [https://support.google.com/accessibility/android/answer/6122836?hl=en](https://support.google.com/accessibility/android/answer/6122836?hl=en)  
    (The above page has an embedded video with a good explanation of switch
    access.)

-   Switch Control for iPhone, iPad, or iPod touch:  
    [https://support.apple.com/en-us/HT201370](https://support.apple.com/en-us/HT201370)

# Table of Contents
{{TOC}}

# Introduction and Terminology
The following terms are used in the proposals in this document.

-   **Single-switch control** means a control like a button that has two
    possible states: active and inactive.

-   **Two-switch control** means a control like a one-dimensional joystick that
    has three possible states, for example: up, down, and inactive.

The representative mobile device for the purposes of describing and illustrating
the proposals has some or all of the following features.

-   Screen on the front of the device.
-   Front-facing camera.
-   Rear-facing camera.
-   Fingerprint sensor.
-   Proximity sensor.
-   Microphone.
-   Accelerometer.

The device could be in one of several positions including the following.

-   Held in one or both of the user's hands.
-   Attached to a frame, for example on the user's wheelchair.
-   Placed on a table or desk.

In some of these positions, there would be open space behind and in front of the
device.

## Diagram: Representative Mobile Device
Representative locations of the screen and cameras are illustrated in the
following diagram.

![**Diagram 1:** Representative device with front and rear cameras](adhoc01_RepresentativeDevice1.svg)

## Switch Control for Text Entry
One use of switch controls is for text entry. There are a number of approaches
to assisted text entry that can be adapted to switch control.

-   Cycle through a list of characters.

    For example, if the user has a two-switch control:

    -   The first switch moves a highlight through a list of characters.
    -   The second switch selects the highlighted character.

    For example, if the user has a single-switch control:

    -   A highlight cycles through a list of characters continuously at a fixed
        speed.
    -   Activating the switch selects the highlighted character.

-   Steer through a zooming user interface.

    The easiest way to understand this could be to watch the following short
    videos.

    -   Text entry in Dasher software controlled by an two-switch control, with
        voice over explanation. Duration is two minutes.

        [https://youtu.be/HzbBTIhd4TU](https://youtu.be/HzbBTIhd4TU)
    
    -   Text entry in Dasher software controlled by a single switch. Duration is
        40 seconds.

        [https://youtu.be/aTCJqpdwV6k](https://youtu.be/aTCJqpdwV6k)

        There isn't a voice over. Here's what's happening:

        -   The moving red box highlights a region of the screen.
        -   The highlight cycles through a number of positions.
        -   The user activates the switch when the highlight is at the required
            position.

# Basic Camera Proposals
It is proposed that the built-in cameras of a mobile device could be used as an
alternative to a separate switch control connected to the device. There are
several ways in which this could be implemented.

## Covering either camera as a two-switch control
Covering either of the built-in cameras of a mobile device could be used as an
alternative to a separate two-switch control connected to the device. For the
purposes of this description, the two switches are designated up and down.

The basic interactions would be as follows.

-   To activate the up switch, the user covers the front-facing camera.
-   To activate the down switch, the user covers the rear-facing camera.
-   To activate neither switch, or between activations, the user covers neither
    camera.

Some further interactions are as follows.

-   To activate the down switch twice, the user would cover the rear-facing
    camera, then uncover it, then cover it again.

### Diagram: Covering either camera as a two-switch control
The above interactions are illustrated in the following diagram.

![**Diagram 2:** Covering either camera as a two-switch control](adhoc02_Cover.svg)

## Gesturing across a camera as a two-switch control
Gesturing across a built-in camera of a mobile device could be used as an
alternative to a separate two-switch control connected to the device. For the
purposes of this description, the two switches are designated up and down.

The basic interactions would be as follows.

-   To activate the up switch, the user makes an upward gesture across the
    camera.
-   To activate the down switch, the user makes a downward gesture across the
    camera.

Some further interactions are as follows.

-   To activate the down switch twice, the user would make a downward gesture
    across the camera, then make a second gesture without crossing the camera.

If a rear-facing camera is used for gestures, then the whole screen would be
visible to the user during the interaction.

### Diagram: Gesturing across a camera as a two-switch control
The above interactions are illustrated in the following diagram.

![**Diagram 3:** Gesturing across a camera as a two-switch control](adhoc03_Gesture.svg)

## Covering a camera as a single-switch control
Covering a built-in camera of a mobile device could be used as an alternative to
a separate single-switch control connected to the device.

The basic interactions would be as follows.

-   To activate the switch, the user covers the camera.
-   To deactivate the switch, or between activations, the user uncovers the
    camera.

If a rear-facing camera is covered and uncovered, then the whole screen would be
visible to the user during the interaction.

## Notes on the basic camera proposals
The following notes apply to the above proposals.

-   The proposals could be adapted for a desktop computer.

    On a laptop or other computer with a built-in webcam, the built-in webcam
    could be used as one camera. An inexpensive USB camera could be used as a
    second camera. Or two USB cameras could be used.

-   The approach could be adapted for users without hands or who cannot move
    their hands.

    The diagrams in the preceding descriptions show hands being moved in various
    ways. A prosthesis could be used instead, or perhaps the user could make a
    similar motion with their foot.

    Switch control by means of facial movements detected by a camera is already
    well known. For example, a user could stick out their tongue to activate a
    single switch.

See also the [Notes on all proposals], below.

# Supplementary Camera Proposals
The preceding section proposed that the built-in cameras of a mobile device
could be used as an alternative to a separate switch control connected to the
device. The specific proposals involved the user moving their hands in relation
to the device cameras.

It is further proposed that the user's hands could be supplemented in order to
make the movements easier to detect. There are several ways in which the hands
could be supplemented.

## Gloves
The user could wear coloured gloves to differentiate their left and right hands.
They could then use the device camera as an alternative to a separate two-switch
control connected to the device. For the purposes of this description, the two
switches are designated up and down.

The procedure would be as follows.

-   Wear a green glove on the left hand.
-   Wear a red glove on the right hand.
-   To activate the up switch, the user puts their left hand in front of one of
    the device cameras.
-   To activate the down switch, the user puts their right hand in front of one
    of the device cameras.
-   To activate neither switch, or between activations, the user puts neither
    hand in front of a device camera.

It is assumed that a device camera and image processing software can
differentiate between green and red coloured gloves more easily than between a
right and left hand, or between the front and back of a hand.

Depending on the level of disability of the user, assistance might be required
to put on the gloves.

## Diagram: Gloves
The above interactions are illustrated in the following diagram.

![**Diagram 4:** Supplemental use of gloves](adhoc04_Gloves.svg)

## Patches
The user could attach patches to their hand to differentiate the front and the
back. They could then use the device camera as an alternative to a separate
two-switch control connected to the device. For the purposes of this
description, the two switches are designated up and down.

The procedure would be as follows.

-   Attach different and detectable patches to the front and back of the hand.

    Patches could be as follows, for example.

    -   Two patches of different colours, such as green on the palm, and red on
        the back.
    -   A patch with one QR code on the palm, and a patch with a different QR
        code on the back.
    -   Two patches with different colours and different QR codes.
    
    Patches could be attached in different ways, depending on user preference
    and other factors. Some examples are as follows.

    -   Sticky labels.
    -   Cards attached to a ring on the user's finger.
    -   Transfers aka temporary tattoos.

-   To activate the up switch, the user presents the back of their hand to the
    device camera.
-   To activate the down switch, the user presents the palm side of their hand
    to the device cameras.
-   To activate neither switch, or between activations, the user puts neither
    hand in front of the device camera.

It is assumed that a device camera and image processing software can
differentiate between green and red coloured patches and QR codes more easily
than between a right and left hand, or between the front and back of a hand.

Depending on the level of disability of the user, assistance might be required
to attach the patches.

## Diagram: Patches
The above interactions are illustrated in the following diagram.

![**Diagram 5:** Supplemental use of patches](adhoc05_Patches.svg)

# Fingerprint Sensor Proposal
It is proposed that the built-in fingerprint sensor of a mobile device could be
used as an alternative to a separate single-switch control connected to the
device.

The basic interactions would be as follows.

-   To activate the switch, the user covers the sensor.
-   To deactivate the switch, or between activations, the user uncovers the
    sensor.

Note that there is no need to recognise the fingerprint as a biometric
identifier.

If the sensor is on the back of the device, then the whole screen would be
visible to the user during the interaction.

# Proximity Sensor Proposal
It is proposed that the built-in proximity sensor of a mobile device could be
used as an alternative to a separate single-switch control connected to the
device.

The basic interactions would be as follows.

-   To activate the switch, the user moves, for example, their hand close to the
    device.
-   To deactivate the switch, or between activations, the user moves, for
    example, their hand away from the device.

The whole screen could be visible to the user during the interaction, depending
on the location and sensitivity of the device sensor.

For background, see the following links.

-   For Android

    -   overview of sensors:  
        [developer.android.com/.../sensors_overview](https://developer.android.com/guide/topics/sensors/sensors_overview)

    -   details of proximity sensors are on the position sensors page:  
        [developer.android.com/.../sensors_position](https://developer.android.com/guide/topics/sensors/sensors_position)

-   For iOS

    -   proximity sensor capability checking:  
        [developer.apple.com/...isproximitymonitoringenabled](https://developer.apple.com/documentation/uikit/uidevice/1620017-isproximitymonitoringenabled)

    -   proximity sensor monitoring:  
        [developer.apple.com/...proximitystatedidchangenotificat](https://developer.apple.com/documentation/uikit/uidevice/1620046-proximitystatedidchangenotificat)

# Microphone Proposal
It is proposed that the built-in microphone of a mobile device could be used as
an alternative to a separate single-switch control connected to the device.

The basic interactions would be as follows.

-   To activate the switch, the user taps or scratches the microphone.
-   To deactivate the switch, or between activations, the user leaves the
    microphone alone.

# Accelerometer Proposal
It is proposed that the built-in accelerometer of a mobile device could be used
as an alternative to a separate single-switch control connected to the device.

The basic interactions would be as follows.

-   To activate the switch, the user hits or shakes the device.
-   To deactivate the switch, or between activations, the user leaves the
    device alone.

This alternative seems most useful in cases where the device is fixed in a frame
or otherwise restrained. When the user hits the device, the restraint would
prevent it from being knocked away, but the accelerometer would still register
the movement.

# Notes on all proposals
The following notes apply to all the above proposals.

-   Alternative switch control options as proposed needn't be implemented in the
    mobile device operating system (OS).
    
    The OS is where switch control is implemented for the device user interface
    in general. The OS could implement alternative switch controls. However,
    alternative switch controls could also be implemented elsewhere.

    An app that has access to the device cameras or other proposed sensors could
    implement alternative switch controls. The scope would be the app's own user
    interface. Implementation code could be in a library or other module. Access
    to cameras and other sensors can depend on system permissions and these are
    typically granted at the app level, not to libraries.

    A custom virtual keyboard, aka on-screen keyboard, that has access to the
    device cameras or other proposed sensors could implement alternative switch
    controls. The scope would be text entry in any app. A custom keyboard could
    be an Input Method Service, for Android, or a Keyboard Extension, for iOS,
    for example. See the following for background.

    -   [developer.android.com/.../InputMethodService](https://developer.android.com/reference/android/inputmethodservice/InputMethodService)
    -   [developer.apple.com/.../creating_a_custom_keyboard](https://developer.apple.com/documentation/uikit/keyboards_and_input/creating_a_custom_keyboard)

    There is already a Dasher text entry custom keyboard for Android and iOS.
    See:  
    [https://github.com/dasher-project/redash/tree/master/Keyboard](https://github.com/dasher-project/redash/tree/master/Keyboard).

-   Switch controls are quite expensive.

    For example, the [iSwitch](https://www.pretorianuk.com/iswitch), a single
    button Bluetooth switch made by Pretorian Technologies costs £142.80. Just
    for comparison, that's approaching ten times the cost of the
    [Active Strike Pro Mini](https://www.amazon.co.uk/TECHGEAR-Bluetooth-Wireless-Keyboard-Touchpad/dp/B014LECNK0?th=1),
    a small Bluetooth keyboard made by Techgear that costs £14.95.

    There are USB cameras on offer for £5 including postage. For example, the
    [CamKpell Mini Webcam](https://www.amazon.co.uk/Million-Computer-Microphone-Desktop-Calling/dp/B07VTSDFFR/).

# Document Information
This document is for internal circulation only.

## Attribution
Words and pictures by Jim Hawkins.

The hand graphic in the diagrams is based on an image downloaded from here:  
[https://publicdomainvectors.org/en/free-clipart/Palm-pictogram/70133.html](https://publicdomainvectors.org/en/free-clipart/Palm-pictogram/70133.html)  
The image is in the public domain.
