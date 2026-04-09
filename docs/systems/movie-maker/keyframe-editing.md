---
title: "Keyframe Editing"
icon: "🔑"
created: 2025-06-30
updated: 2025-07-03
---

# Keyframe Editing

![](./images/keyframe-editing.png "right-50 =223x135")This is the simplest way to describe how stuff in your scene should animate. Create keyframes in property tracks that are snapshots for what values that track should have at specific times, then control how the track should blend between those values.

It will be active by default, but you can toggle it with the key-shaped button in the toolbar.


## Creating Keyframes

There's three ways to create a keyframe for a property track:

* Change the property that the track is bound to, a keyframe is created at the current playhead time
* Right-click on the track in the timeline, and select *Create Keyframe* in the context menu
* Toggle *Create Keyframe on Click* either by holding Shift or pressing the button in the toolbar, then clicking in the timeline

  \

[sbox-dev_iAf40itXRB.mp4 1008x896](./images/sbox-dev-iaf40itxrb.mp4)


:::tip
Copy the scene view's perspective into a selected camera with Ctrl+Shift+F

:::


## Interpolation Mode

Each keyframe can choose between three different interpolation modes:

* Linear - change at a constant velocity
* Quadratic - ease in / out, with 0 velocity at the keyframe
* Cubic - move along a smooth spline connecting keyframes


[sbox-dev_6y9byeniJF.mp4 1008x896](./images/sbox-dev-6y9byenijf.mp4)

You can combine different modes for neighbouring keyframes to make animations ease in or out.


[sbox-dev_ThsOOsr9bq.mp4 1008x896](./images/sbox-dev-thsoosr9bq.mp4)


## Automatic Track Creation

For convenience, you can enable this mode to create tracks whenever you touch something in the scene. This helps the most when you're changing lots of properties on many objects, so you don't have to manually created dozens of tracks.


[sbox-dev_yRfCXPdJl1.mp4 1482x896](./images/sbox-dev-yrfcxpdjl1.mp4)
