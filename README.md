# OverTheWire Bandit Labs --- Levels 0--33

**Independent hands-on Linux and cybersecurity lab documentation**

## Overview

This repository documents my independent work through the OverTheWire
Bandit wargame, covering Levels 0--33. I created the accompanying
technical documentation myself, recording the objectives, commands used,
and the practical steps I followed while working through the challenges.

The lab helped me practise Linux command-line usage and build
familiarity with common system administration and security tools.

## Lab coverage

The documentation covers the following challenge areas, as reflected in
my lab notes:

-   SSH access and authentication
-   Linux filesystem navigation and file inspection
-   Hidden files, unusual filenames, and file identification
-   File ownership, permissions, and searching
-   Text processing and extracting information from files
-   Base64 decoding and ROT13
-   Hex dumps and repeatedly compressed files
-   SSH private-key authentication
-   Local network services and TCP connections
-   SSL/TLS connections using OpenSSL
-   Port discovery and service identification with Nmap
-   Comparing files and identifying changed lines
-   Shell behaviour and restricted-shell escape concepts
-   Setuid binaries and privilege-related concepts
-   Cron jobs and scheduled scripts
-   Shell scripting
-   Git repositories and repository history/content inspection

## Tools and commands practised

The notes include practical use of tools and commands such as:

`ssh`, `ls`, `cd`, `cat`, `file`, `du`, `find`, `grep`, `sort`, `uniq`,
`strings`, `base64`, `tr`, `tar`, `gzip`, `bzip2`, `xxd`, `mkdir`, `cp`,
`mv`, `chmod`, `nc`, `openssl s_client`, `nmap`, `diff`, `cron`, and
`git`.

## What I learned

-   Navigate a Linux environment from the command line.
-   Connect to remote systems using SSH.
-   Inspect files and locate information using standard Linux utilities.
-   Work with encoded, compressed, and hexadecimal data.
-   Explore network services and encrypted connections.
-   Read scripts and understand scheduled task execution.
-   Use Git repositories as part of a command-line workflow.
-   Troubleshoot challenges independently and document the process.

## Repository structure

A suggested structure for this repository:

``` text
OverTheWire-Bandit-Labs/
├── README.md
├── BANDIT-LABS.pdf
├── writeups/
│   ├── levels-00-10.md
│   ├── levels-11-20.md
│   └── levels-21-33.md
├── screenshots/
│   └── (sanitized terminal screenshots)
└── skills-learned.md
```

The PDF and supporting folders should be added after reviewing and
sanitizing the original document.

## Security and responsible disclosure

-   Do **not** publish Bandit passwords, private SSH keys, tokens, or
    other credentials.
-   Review screenshots and terminal history before uploading them.
-   Keep writeups focused on the learning process and commands; redact
    secrets and credential values.
-   Use these techniques only in systems and labs where you have
    permission.

## About this project

This is a self-directed learning project. I independently worked through
the Bandit levels and authored the technical notes to record my process
and learning.

**Platform:** OverTheWire Bandit\
**Coverage documented:** Levels 0--33\
**Focus:** Linux fundamentals and practical security skills

OverTheWire is the creator of the Bandit wargame. This repository is an
independent learning record and is not an official OverTheWire
publication.
