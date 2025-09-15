markdown

Beginner's Setup Guide for Monad

This guide is for absolute beginners who want to get started with the Monad project. It explains how to set up the project on your local machine and run it successfully.

Requirements

Make sure you have the following installed:

  Git
  Go (Golang) version 1.20 or later
  make (build tool)
  A Unix-based terminal (macOS, Linux, or WSL for Windows)

Steps to Get Started

1. *Fork the Repository*

Go to the official Monad GitHub repo and fork it to your account.

2. *Clone Your Fork*

Open your terminal and run:

bash
git clone https://github.com/ngozicynthia/monad.git
cd monad


3. *Build the Project*

Inside the project folder, run:

bash
make build
This will build the Monad project locally.

4. *Run Tests*

To verify that everything is working:

bash
make test

If all tests pass, your setup is complete.
Common Issues

 Make sure your Go version is correct by running go version.
 If make doesn’t work, check if it’s installed and you’re in the right folder.
 Use go install if you get any missing dependency errors.

Notes:

This guide is written from a beginner's point of view and may be helpful for other new contributors. Feel free to improve or update it.

Made with 💜 by a new contributor to Monad.
