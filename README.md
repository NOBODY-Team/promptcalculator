# [directory](https://nobodyteam.com)

# PromptCalculator
Is an ultraminimalistic open-source command based calculator, that includes both normal calculator functionality, and more advanced text command based functions.

PromptCalculator is in constant development, and we would love to hear your feedback on any additions that could be made to the software and/or issues that should be addressed!

![{701B7182-5D2D-450E-BEC8-13720B588878}](https://github.com/user-attachments/assets/39baf561-0ec5-4abc-9259-973f9c328635)

# Video Showcase

{% include youtube.html id="7inYxAwPpI4" %}

# Installation

## Current Version: V2

## [Direct Install (Github)](https://github.com/NOBODY-Team/promptcalculator/releases/download/V2/PromptCalculator.zip)
## [Github (Releases Page)](https://github.com/NOBODY-Team/promptcalculator/releases/tag/V2)
## [Source](https://nobodyteam.com/promptcalculator/#source-1)

## Changelog

```
[V2] - Fixed the output not being automatically cleared due to a line calculation error.
```


# Education

In case any educational facility wishes to utilize PromptCalculator, we will gladly take suggestions on functionality that would be required, and provide tech support for any endeavours related to integrating PromptCalculator into any facility systems, all for free. NOBODY wholeheartedly believes that education should be easy and free. For inquiries relating to this, contact [education@nobodyteam.com](mailto:education@nobodyteam.com).

# Functionality

# General

> Operational Range becomes higher each update

| Functionality | Explanation | Example |
| --- | --- | --- |
| Operational Range | The current maximum operational range of PromptCalculator. | `999 * 10 ^ 305` is the current maximum operational range. |
| Operation Submitting | The input that submits the current operation | Operations can be submitted by typing `=`, pressing `Enter` or by pressing `the left mouse button (Mouse0)`. |
| Scientific Formatting | High numbers will be output in the scientific format. | `999 * 10 ^ 305` would be output as `9.99E+307`. |
| Multinational Input Support | Both `Comma (,)` and `Dot (.)` are valid input methods. | Inputting `2.22 * 2` would be output as `4.44`, and inputting `2,22 * 2` would output as `4,44`. |

# Commands

## Mathematical

> All commands can be viewed in-software by typing `help` as the prompt

### Basic

| Command | Explanation | Example |
| --- | --- | --- |
| `/ref/` | Reference to the result of the previous submitted operation | `/ref/ * 2 = 4` (if previous operation was `1 + 1`) |
| `/plus/ or +` | Addition | `2 /plus/ 2` or `2 + 2`. |
| `/minus/ or -` | Subtraction | `2 /minus/ 2` or `2 - 2`. |
| `/times/ or *` | Multiplication | `2 /times/ 2` or `2 * 2`. |
| `/div/ or /` | Division | `2 /div/ 2` or `2 / 2`. |
| `/exponent/ or ** or ^` | Exponentiation | `2 /exponent/ 2` or `2 ** 2` or `2 ^ 2`. |

### Advanced

| Command | Explanation | Example |
| --- | --- | --- |
| `/accuracy[number]` | Sets the output's decimal accuracy. Default is 2. | `2.23274382 * 3 /accuracy6` would output the operation with six decimals. |
| `/pi/` | Value of pi | `/pi/ * 2 / 3` would output `2.09`. |
| `/squarerootof[number]` | Squareroot of the number defined | `/squarerootof100` would output the squareroot of 100; 10. |
| `/cubeerootof[number]` | Cuberoot of the number defined | `/cuberootof-1000` would output the cuberoot of -1000; -10. |

# Source

PromptCalculator is developed with [Unity](https://unity.com/), and by extension, C#. 

The current release was more specifically developed with Unity 6000.0.12f1 and the Built-in Render Pipeline.

> [WARNING!]
> The source code of the current version consists of a singular uberscript, CMD.cs, containing `405 lines`, and barely any comments, so understanding it may be slightly hard. We are aiming to expand the source with comments in future versions.

## Source Install

### [Github (Releases Page)](https://github.com/NOBODY-Team/promptcalculator/releases/tag/V2-Source)

### [Direct Install (Github)](https://github.com/NOBODY-Team/promptcalculator/releases/download/V2-Source/PromptCalculatorSource.unitypackage)

## Installation Instructions

1. Install the .unitypackage from either of the above links
2. Install any Unity 6 version
3. Install the Built-in Render Pipeline
4. Create an empty project
5. Drop the .unitypackage in the Assets folder

# Feedback & Issues

## Issue List

> This list goes through issues we are aware of.

```
- Windows regional format somehow affects the functionality, despite this supposedly being completely impossible. In case you have the Finnish regional format, /pi/ may be invalid and /pii/ may be the only option, and European regional formats may be forced to comma automatically. This is not intended, and will be fixed in V3.
- Non-mathematical commands will be displayed as an invalid calculation in the predictive output field
- Maximum operational range is not high enough
- Formatting may be too confusing
```

## Feedback Email

### [All Contact Emails](https://nobodyteam.com/contact)

### General Feedback: [feedback@nobodyteam.com](mailto:feedback@nobodyteam.com)

### PromptCalculator: [promptcalculator@nobodyteam.com](mailto:promptcalculator@nobodyteam.com)

