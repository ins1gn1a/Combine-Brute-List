#!/usr/bin/env python3

import sys

if (len(sys.argv)) < 3:
        sys.exit("Usage: ./combineBruteList.py username.txt password.txt")

with open(sys.argv[1], 'r') as f:
        for fLine in f:
                with open(sys.argv[2], 'r') as g:
                        for gLine in g:
                                combined = (fLine.rstrip() + ":" + gLine.rstrip())
                                print (combined)
