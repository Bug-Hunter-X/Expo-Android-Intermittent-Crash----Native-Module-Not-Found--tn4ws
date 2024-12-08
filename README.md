# Expo Android Intermittent Crash - 'Native Module Not Found'

This repository demonstrates a bug encountered in an Expo application resulting in intermittent crashes on Android devices. The error logs provided by the application were insufficient for quick debugging, reporting only a generic 'native module not found' message. The inconsistency of crashes across different Android devices further complicated the issue.

## Bug Reproduction

The `bug.js` file showcases the code that produced the error.  While the precise cause wasn't directly identifiable in the original code (because of the inconsistency), this example simulates the circumstances.  Note that you'll need to have an Expo project properly configured to reproduce the problem fully.

## Solution

The `bugSolution.js` file demonstrates a possible solution to the issue. Note that the real solution may vary depending on the specific module involved and the true cause of the crash. This demonstrates potential approaches to solve the problem, which include: double-checking module installation; verifying the proper usage of modules in specific contexts; and handling potential errors gracefully.

## Contributing

Feel free to contribute by improving the reproduction steps or providing alternative solutions.