# [directory](https://nobodyteam.com)

# PromptCalculator
Is an ultraminimalistic open-source command based calculator, that includes both normal calculator functionality, and more advanced text command based functions.

PromptCalculator is in constant development, and we would love to hear your feedback on any additions that could be made to the software and/or issues that should be addressed!

![{701B7182-5D2D-450E-BEC8-13720B588878}](https://github.com/user-attachments/assets/39baf561-0ec5-4abc-9259-973f9c328635)

# Installation
## [Direct Install (Github)](https://github.com/NOBODY-Team/promptcalculator/releases/download/V1/PromptCalculator.zip)
## [Github (Releases Page)](https://github.com/NOBODY-Team/promptcalculator/releases/tag/V1)
## [Source](https://nobodyteam.com/promptcalculator/#source-1)

# Video Showcase

[Showcase](https://youtu.be/7inYxAwPpI4?si=4TuArR0Mg1OrYHcL)

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
