# README

This project is actually in wip status.  
All features aren't ready for now.

Use at your own risks.

## Introduction

This ansible playbook is designed to deploy development environment on remote hosts easily.

## Language support

| Name | Version                |
| ---- | ---------------------- |
| Ruby | Selectable with rbenv  |
| PhP  | Selectable with phpenv |

## Compatibles distributions

| Name          | Version       |
| ------------- | ------------- |
| Debian        | 10 (buster)   |
| Debian        | 11 (bullseye) |
| CentOS        | 7             |
| RockyLinux    | 8             |
| RedHat EL     | 8             |
| OpenSUSE Leap | 15            |

## Testing process

All the playbook was fully tested :
- All role was linted before each commit.
- All modifications was validated with molecule to perform deployment and idempotence check (except for RHEL 8).
- All modifications was validated with virtual machines for each OS supported.

## Changelog
- 2021-07-16 - WIP : Adding fully working rbenv role
