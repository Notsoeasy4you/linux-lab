# Linux Log Analysis Lab

## Objective
Learn how to inspect and analyze system logs.

## View system logs

Command:
journalctl

## View latest logs

journalctl -n 20

## Follow logs in real time

journalctl -f

## View SSH logs attempts

journalctl | grep ssh

## View failed logins

journalctl | grep "Failed"

## View sudo usage

journalctl | grep sudo
