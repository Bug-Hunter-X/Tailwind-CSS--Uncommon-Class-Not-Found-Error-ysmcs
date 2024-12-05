# Tailwind CSS: Uncommon Class Not Found Error

This repository demonstrates a common, yet sometimes subtle, error in Tailwind CSS: using a class that isn't defined in your configuration file. This usually manifests as the style simply not being applied.

The `bug.js` file shows the incorrect usage, while `bugSolution.js` provides the correct implementation.  The core problem is ensuring all used classes are either explicitly listed in `tailwind.config.js` or that the `content` option correctly identifies all your template files.