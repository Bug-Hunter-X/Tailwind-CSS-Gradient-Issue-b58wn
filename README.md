# Tailwind CSS Gradient Issue

This repository demonstrates a bug related to gradient functionality in Tailwind CSS.  The gradient doesn't render correctly, exhibiting distortions or failing to appear altogether.

## Bug Description
The issue occurs when using the `bg-gradient-to-r` utility class in combination with color specifications (`from-blue-500 to-purple-500`). The expected behavior is a smooth, horizontal gradient from blue to purple. Instead, the actual output varies depending on the browser or other factors.

## Solution
The solution might involve carefully checking the Tailwind CSS configuration, ensuring that the necessary plugins are enabled and that there aren't any conflicting styles.  Additionally, browser-specific adjustments may be required.  The solution file includes a corrected implementation.