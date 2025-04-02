# Chip Module C API Documentation

## Overview
This document provides the API specifications for the Chip Module library, written in C. It includes functions for GPIO pin management, commonly used in embedded systems.

## GPIO Functions

### init_gpio
Initializes a GPIO pin with a specified mode.

```c
void init_gpio(uint8_t pin, uint8_t mode);
// Initializes GPIO pin with specified mode
// Parameters:
//   - pin: The pin number (0-31)
//   - mode: 0 for input, 1 for output
// Returns: None
