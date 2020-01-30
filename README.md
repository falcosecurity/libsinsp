# libsinsp

### Glossary

✖ This is not a `spec`.

✖ This is not a binary program you execute.

✔ This is a library written in C++.

✔ This allows to capture events from a live Operating System

### What it is

libsinsp is a system inspection library that implements high level
functionality like:

- live capture control (start/stop/pause...)
- event capture from file or the live OS
- OS state reconstruction. By parsing /proc and inspecting the live event stream,
libsinsp is capable of mirroring the OS process state and putting context around
key OS primitives like process IDs and file descriptors. That way, these primitives
can be treated like programs, files, connections and users.
- parsing of OS events and conversion of events into human-readable strings
- event filtering
