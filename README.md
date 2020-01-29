# virtualenv_cpp

A small script to setup a virtualenv with a local python installation and local C++ libs.

You can put you C++ lib sources (git) into `requirements_cpp_git.txt`.

The file `requirements_cpp_git.txt` is pre-filled with an example.

(The script is just a quick solution for my ubuntu machine - some adaptations may be needed for other systems).

## Requirements

 * python3, virtualenv, cmake, g++

## Usage

 * ./activate_env
 * (work in your env)
 * exit
 
The first time the activate script will download and install your libs.
