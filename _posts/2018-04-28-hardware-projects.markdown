---
layout: post
title: Hardware Projects
date: 2018-04-28 13:32:20 +0530
description: My Hardware Projects
img:  # Add image post (optional)
hidden: true
tags: [Prasanta, Details, hardware, projects]
---

## Basic VHDL Coding

#### 1. 32-bit Single Precision Floating Point Adder

Floating Point Adder in VHDL and Verification of result with matlab code. TThis project was done as a help assignment of a junior friend. It demonstrates the use of Windows Multimedia SDK, Win32 GUI and custom data structure.

The project uses the IEEE-754 Single Precision floating point format. The following table lists how the 32-bit floating number is divided into 3 parts viz. Mantissa, Exponent and the Sign bit of length 23, 8 and 1 bits accordingly.

Using the above format, the floating point number can be expressed as follows -

| (-1)*sign 1.mantissa x 2 ^ exponent |

In the IEEE-754 format the first bit of mantissa is assumed to be 1 and the remaining part is the fractional part.
