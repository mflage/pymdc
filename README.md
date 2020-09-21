# Multi Display Control (MDC) protocol implementation in Python

Python interface for using the Multi-Display Control (MDC) protocol. This is used mainly by Samsung Digital Signage TVs

## TODO

Implement the full MDC protocol, currently only powering on/off is supported.

## Examples

import pymdc

mdc = pymdc.MDC(host="127.0.0.1")

