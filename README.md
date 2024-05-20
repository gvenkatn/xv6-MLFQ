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
```

2. Follow the instructions in the xv6 documentation to build and run the operating system.
```bash
chmod ugo+x ./sign.pl
make clean
make qemu-nox
```

3. Run the test file
```bash
schdtest
```

## Usage
After installing the MLFQ implementation in xv6, you can test its functionality by running various user programs and observing their scheduling behavior. Additionally, you can modify the MLFQ parameters and algorithms to optimize performance for specific workloads.

## Contributing

We welcome contributions from the community to enhance the MLFQ implementation in xv6. If you'd like to contribute, please follow these steps:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/new-feature`.
3. Make your changes and ensure they follow the coding style and guidelines.
4. Test your changes locally to ensure they work as expected.
5. Commit your changes with descriptive commit messages: `git commit -m "Add new feature"`.
6. Push your changes to your fork: `git push origin feature/new-feature`.
7. Open a pull request against the `main` branch of this repository.
8. Provide a clear description of your changes in the pull request, including any relevant information for reviewers.
9. Participate in the code review process and address any feedback or comments.
10. Once your changes are approved, they will be merged into the main repository.

Thank you for contributing to our project!

**Disclaimer:** This project should not be used for university coursework projects. The contributors are not responsible if individuals are caught for plagiarism or academic dishonesty while using this project for such purposes.
