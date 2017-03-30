# gocsv

## Extension to standard go encoding/csv package to handle quotes and skip header lines

This code is used exactly the same as the standard [encoding/csv](https://golang.org/pkg/encoding/csv/) package in golang the only differences are:
1. Both the Reader and Writer has a field Quote; which can be used to use a different quote character than the default "
2. The Reader has a field SkipHeader; when set to true the first line in the input is skipped.

