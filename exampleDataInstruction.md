<!--
 * @Author: your name
 * @Date: 2021-04-26 14:32:58
 * @LastEditTime: 2021-04-27 14:47:47
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /meson-scheduling/exampleDataInstruction.md
-->

# Example Data Instruction

## TerminalInfoExample

file: nodeInfoExample.xlsx

The data in the file is sample data which is part of the terminal information.
There are some important indicators that can be used as input for scheduling algorithm.

important column in TerminalInfoExample:

**speed_Mbs(bandwidth Mbits/s):** Data from SpeedTester. Bandwidth of terminals.

**cdn_disk_total_GB:** The storage space provide by terminal.

**cdn_space_usage(%):** How many storage already be used.

## FileRequestExample

FileRequestInfo: fileRequestExample.xlsx

The record of file access requests, including the size of the file, the number of accesses in the two statistical time periods, and the change in access frequency.

