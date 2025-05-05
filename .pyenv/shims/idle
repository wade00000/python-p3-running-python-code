#!/usr/bin/env bash
set -e
[ -n "$PYENV_DEBUG" ] && set -x

program="${0##*/}"

export PYENV_ROOT=".pyenv"
exec "/home/wade/.pyenv/libexec/pyenv" exec "$program" "$@"
