# Multi-Level Feedback Queue (MLFQ) Implementation in xv6

This repository contains an implementation of the Multi-Level Feedback Queue (MLFQ) scheduling policy in the xv6 operating system.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Multi-Level Feedback Queue (MLFQ) is a scheduling algorithm that provides a balance between response time and turnaround time for processes in an operating system. It achieves this by maintaining multiple queues with different priority levels and dynamically adjusting the priority of processes based on their behavior and resource usage.

This repository extends the xv6 operating system with MLFQ scheduling support, allowing for more efficient process management and improved system responsiveness.

## Features

- Implementation of the MLFQ scheduling policy in xv6.
- Multiple queues with different priority levels.
- Dynamic adjustment of process priorities based on resource usage and behavior.
- Improved system responsiveness and efficient process management.

## Getting Started

To get started with using or contributing to this MLFQ implementation in xv6, follow the instructions below.

### Prerequisites

- Basic knowledge of the C programming language.
- Familiarity with the xv6 operating system architecture.

### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/mlfq-xv6.git

2. Follow the instructions in the xv6 documentation to build and run the operating system.
```bash
chmod ugo+x ./sign.pl
make clean
make qemu-nox

## Usage
After installing the MLFQ implementation in xv6, you can test its functionality by running various user programs and observing their scheduling behavior. Additionally, you can modify the MLFQ parameters and algorithms to optimize performance for specific workloads.
