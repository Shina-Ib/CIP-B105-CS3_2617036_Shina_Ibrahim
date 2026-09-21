# Overview

This project presents a Windows memory forensics investigation using Volatility 2 to determine whether a suspect downloaded a file and transferred it to removable storage. The investigation combines multiple memory-resident artefacts, including Registry hives, user accounts, processes, network connections, command history, browser activity, Shellbags, and USB device information.

The analysis correlates Chrome download evidence, command-line activity, USB identifiers, drive-letter assignments, user associations, and timestamps to reconstruct the sequence of events. The findings are consolidated into a corrected UTC timeline, demonstrating how multiple independent forensic artefacts can be used to corroborate user activity and establish a defensible evidence trail.
