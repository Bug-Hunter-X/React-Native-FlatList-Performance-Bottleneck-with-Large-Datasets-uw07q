# React Native FlatList Performance Optimization

This repository demonstrates a common performance issue in React Native's FlatList component when dealing with large datasets and provides a solution for optimization.

## Problem
When rendering a large number of items in a FlatList, inefficient key management or complex item components can lead to significant performance degradation, causing slow scrolling, dropped frames, and potentially app crashes.

## Solution
The solution involves implementing proper key extraction using the `keyExtractor` prop and optimizing the components rendered within each list item. This ensures React Native's diffing algorithm can efficiently update the list, leading to smoother scrolling and improved performance.

## Usage
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npx react-native run-android` or `npx react-native run-ios` to run the app.