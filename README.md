# AA-Texts

This tool is meant to quickly take notes of coordinates when playing Minecraft All Advancements speedruns.

Download [here](https://github.com/Antoine-MSL/AA-Texts/releases) then just unzip the file and open main.exe

It's pretty poorly coded but it works okay, only with a few specific formats. If you try other things you will get errors so yeah follow the following formats if you wanna use that tool

## Supported formats + Examples

### [label (optional)] [f3+c]

**<ins>Example:</ins>**

<ins>Input:</ins>

Bastion /execute in minecraft:the_nether run tp @s 194.18 104.00 -202.44 31.01 44.04

<ins>Output:</ins>

Bastion

1552, -1616

194, -202

-----

### [f3+c] [label (optional)]

**<ins>Example:</ins>**

<ins>Input:</ins>

/execute in minecraft:overworld run tp @s 1984.18 104.00 2012.44 31.01 44.04 only one panda

<ins>Output:</ins>

only one panda

1984, 2012

248, 251

-----

### \*[X (overworld)] [Y (overworld)] [label (optional)]

**<ins>Example:</ins>**

<ins>Input:</ins>

\*2000 1000 Outpost

<ins>Output:</ins>

Outpost

2000, 1000

250, 125

-----

### \**[X (nether)] [Y (nether)] [label (optional)]

**<ins>Example:</ins>**

<ins>Input:</ins>

\*\*400 -600

<ins>Output:</ins>

\-

3200, -4800

400, -600

-----

### \*\*\*[X (end)] [Y (end)] [label (optional)]

**<ins>Example:</ins>**

<ins>Input:</ins>

\*\*\*2400 1600 Gateway

<ins>Output:</ins>

Gateway

2400, 1600

(The End)
