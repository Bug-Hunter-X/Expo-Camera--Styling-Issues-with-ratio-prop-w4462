# Expo Camera Styling Bug

This repository demonstrates a bug in Expo's Camera component where custom styles are not correctly applied when using the `ratio` prop.  The bug leads to unexpected rendering behavior, often resulting in incorrect aspect ratios.

## Bug Description

When applying custom styles (e.g., `flex: 1`, specific height/width) to the Camera component in conjunction with a `ratio` prop, the layout may not adhere to the expected aspect ratio. This occurs despite seemingly correct style application.

## Reproduction Steps

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `expo start`.
4. Observe the rendering of the Camera component. The aspect ratio will be incorrect, demonstrating the bug.

## Solution

The solution involves restructuring the layout to ensure correct scaling and aspect ratio handling, leveraging the aspect ratio and style constraints efficiently. The corrected code provides the expected layout and aspect ratio.  The solution file offers a working example using a container to correctly manage aspect ratios.