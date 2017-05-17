#!/bin/bash

pid=$(pidof "mpv")

if [[ "$pid" ]]; then
  kill "$pid"
fi

mpv --player-operation-mode=pseudo-gui "$1"
